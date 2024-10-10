---
title: "SecureImgStego: A Keyed Shuffling-based Deep Learning Model for Secure Image Steganography"
collection: publications
permalink: /publication/2023-08-01-secureimgstego
excerpt: 'In this study, we uncovered the inherent vulnerabilities in deep learning based steganogaphic systems, and proposed simple shuffling based solution to mitigate that.'
date: 2023-08-01
venue: '2023 IEEE Conference on Communications and Network Security (CNS)'
slidesurl: 'https://imranur-rahman.github.io/files/SecureImgStego_CNS2023_slide.pdf'
paperurl: 'https://imranur-rahman.github.io/files/SecureImgStego.pdf'
url_slug: 'https://github.com/imranur-rahman/secureimgstego'
citation: '@inproceedings{chakraborty2023secureimgstego,
  title={SecureImgStego: A Keyed Shuffling-based Deep Learning Model for Secure Image Steganography},
  author={Chakraborty, Trishna and Rahman, Imranur and Murad, Hasan and Hossain, Md Shohrab and Mehnaz, Shagufta},
  booktitle={2023 IEEE Conference on Communications and Network Security (CNS)},
  pages={1--9},
  year={2023},
  organization={IEEE}
}'
---

Steganography ensures secure transmission of digital messages, including image steganography where a secret image is hidden within a non-secret cover image. Deep learning-based methods in image steganography have recently gained popularity but are vulnerable to various attacks. An adversary with varying levels of access to the vanilla deep steganography model can train a surrogate model using another dataset and retrieve hidden images. Moreover, even when uncertain about the presence of hidden information, the adversary with access to the surrogate model can distinguish the carrier image from the unperturbed one. Our paper includes such attack demonstrations that confirm the inherent vulnerabilities present in deep learning-based steganography. Deep learning-based steganography lacks lossless transmission assurance, rendering sophisticated image encryption techniques unsuitable. Furthermore, key concatenation-based techniques for text data steganography fall short in the case of image data. In this paper, we introduce a simple yet effective keyed shuffling approach for encrypting secret images. We employ keyed pixel shuffling, multi-level block shuffling, and a combination of key concatenation and block shuffling, embedded within the model architecture. Our findings demonstrate that the block shuffling-based deep image steganography has negligible error overhead compared to conventional methods while providing effective security against adversaries with different levels of access to the model. We extensively evaluate our approach and compare it with existing methods in terms of human perceptibility, key sensitivity, adaptivity, cover image availability, keyspace, and robustness against steganalysis.
