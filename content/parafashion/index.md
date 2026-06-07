---
title: Parafashion
type: page
---

# Parafashion

## Computational Pattern Making from 3D Garment Models

<div style="margin:1.5rem 0;">
  <iframe width="700" height="394" src="https://www.youtube.com/embed/wsrQiH3zyuI" frameborder="0" allowfullscreen style="max-width:100%;border-radius:8px;"></iframe>
</div>

<div style="margin:1rem 0;">
  <a href="https://dl.acm.org/doi/10.1145/3528223.3530145" target="_blank" style="margin-right:1rem;">📄 Siggraph Paper</a>
  <a href="https://www.dropbox.com/scl/fi/xcv29rxthxu64umpal5yp/parafashion_final_talk.pptx?rlkey=gbellvc3lusj0rkn0s96nn6k1&st=hrj3ytay&dl=0" target="_blank" style="margin-right:1rem;">🎞️ Presentation</a>
  <a href="https://github.com/nicopietroni/parafashion" target="_blank">💻 Source Code</a>
</div>

**[Nico Pietroni](https://nicopietroni.github.io)**, **C Dumery**, **R Guenot-Falque**, **M Liu**, **T Vidal-Calleja**, **[Olga Sorkine-Hornung](https://igl.ethz.ch/people/sorkine/)**

<img src="/publications/paraf_0_edited.avif" style="width:100%;max-width:700px;border-radius:8px;margin:1.5rem 0;">

## Automatic Pattern Layout Decomposition

Our algorithm segments an input 3D garment shape into patches and computes their 2D parameterization, resulting in pattern pieces that can be cut out of fabric and sewn together to manufacture the garment. Unlike the general state-of-the-art approaches for surface cutting and flattening, our method explicitly targets garment fabrication.

## Fabrication Aware

It accounts for the unique properties and constraints of tailoring, such as seam symmetry, the usage of darts, fabric grain alignment, and a flattening distortion measure that models woven fabric deformation, respecting its anisotropic behavior.

<img src="/publications/paraf_1_edited.avif" style="width:100%;max-width:700px;border-radius:8px;margin:1.5rem 0;">

## Interactive

While our algorithm can automatically produce the sewing patterns, it is fast enough to admit user input to creatively iterate on the pattern design. Our method can take several target poses of the 3D garment into account.

<img src="/publications/paraf_2_edited.avif" style="width:100%;max-width:700px;border-radius:8px;margin:1.5rem 0;">
