---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>. Entries tagged <span class="pub-compact__badge">First author</span> are first-authored by me.</div>
{% endif %}

{% include base_path %}

<style>
.pub-compact__year {
  margin: 1.6em 0 0.4em;
  padding-bottom: 0.2em;
  font-size: 1.05em;
  font-weight: 700;
  border-bottom: 2px solid #e3e3e3;
}
.pub-compact__list {
  list-style: none;
  margin: 0 0 0.5em;
  padding: 0;
}
.pub-compact__item {
  padding: 0.5em 0;
  border-bottom: 1px solid #ececec;
  line-height: 1.45;
  font-size: 0.95em;
}
.pub-compact__item:last-child {
  border-bottom: none;
}
.pub-compact__title a {
  font-weight: 600;
  text-decoration: none;
}
.pub-compact__title a:hover {
  text-decoration: underline;
}
.pub-compact__badge {
  display: inline-block;
  margin-left: 0.5em;
  padding: 0.05em 0.5em;
  border-radius: 1em;
  background: #eef6ee;
  color: #2f7a3d;
  font-size: 0.72em;
  font-weight: 600;
  vertical-align: middle;
}
.pub-compact__venue {
  display: block;
  color: #767676;
  font-style: italic;
  font-size: 0.9em;
  margin-top: 0.1em;
}
.pub-compact__link {
  display: inline-block;
  margin-top: 0.15em;
  font-size: 0.85em;
}
</style>

{% assign pubs = site.publications | sort: "date" | reverse %}
{% assign pub_years = pubs | group_by_exp: "post", "post.date | date: '%Y'" %}
{% for year in pub_years %}
  <h2 class="pub-compact__year">{{ year.name }}</h2>
  <ul class="pub-compact__list">
    {% for post in year.items %}
      {% include archive-single-publication.html %}
    {% endfor %}
  </ul>
{% endfor %}
