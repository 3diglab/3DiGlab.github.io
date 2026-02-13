---
title: "From Noise to Image: a Study into the Impact of Noise in Image Generation"
contact_name: Simone Melzi, Lorenzo Olearo
contact_email: simone.melzi@unimib.it, lorenzo.olearo@unimib.it
date: 2026-02-13 00:00:00-0000
assigned: false
image: cat-dog-same-seed.png
tags:
#     - bachelor's
    - master's
    - Computer Vision
    - Generative Models
    - Image Synthesis

---
Modern text-to-image (T2I) pipelines have reached a stage where they can
generate near-photorealistic images. Driven by the increase in popularity since
2020, extensive research has focused on improving visual realism. In contrast,
the equally critical issue of faithfulness, along with the underlying mechanisms
that shape and constrain the generation process, has received comparatively less
attention.

Diffusion models work by gradually adding noise to input data through a
**forward process**, transforming it into pure Gaussian noise. A neural network
is then trained to reverse this process, starting from random noise and
generating new samples that match the original data distribution. This
**reverse process** is what is commonly associated with the generation of
images.

Most state-of-the-art models generate samples through a deterministic process:
starting from a fixed initial noise, the model follows a specific trajectory to
generate a single, corresponding output image. In the context of text-to-image
generation, this process is further guided by a textual description, which,
alongside the initial noise, directs the model toward creating an image that
matches the provided prompt.

Interestingly, the initial noise (or "seed") used in diffusion models often
influences certain visual characteristics of the generated image, such as
composition, pose, or background, regardless of the prompt. For example, if you
generate an image of a “dog” using a specific seed, and then use the same seed
to generate a “cat,” you may notice that both subjects appear in similar
positions and share common visual traits. This demonstrates how the seed itself
can impose structural similarities across different generated images.

Over the past year, the seed’s role in image generation has emerged as a
central topic in generative image synthesis. **This raises a fundamental
question: independently from the prompt, which aspects of the generated image
does the seed actually control?** Answering this question will be the main focus
of this thesis.


#### Expected Outcomes

- Deep understanding of how generative models, particularly diffusion models
  work, with a specific focus on the role of noise in the generation process.

- Experimental analysis of common features across images generated with the same seed, from edges to color distribution, composition, and more.


#### References
- Rombach, Robin, et al. "High-resolution image synthesis with latent diffusion models." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2022.

- Xu, Katherine, Lingzhi Zhang, and Jianbo Shi. "Good seed makes a good crop: Discovering secret seeds in text-to-image diffusion models." 2025 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV). IEEE, 2025.

- Karthik, Shyamgopal, et al. "If at first you don't succeed, try, try again: Faithful diffusion-based text-to-image generation by selection." arXiv preprint arXiv:2305.13308 (2023).
