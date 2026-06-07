---
title: LoopyCuts
type: page
---

# LoopyCuts

## LoopyCuts: Practical Feature-Preserving Block Decomposition

<div style="margin:1.5rem 0;">
  <iframe width="700" height="394" src="https://www.youtube.com/embed/n-rWtLi3LSU" frameborder="0" allowfullscreen style="max-width:100%;border-radius:8px;"></iframe>
</div>

<div style="margin:1rem 0;">
  <a href="https://vcgdata.isti.cnr.it/Publications/2020/LPPSC20/LPPSC20.pdf" target="_blank" style="margin-right:1rem;">📄 PDF</a>
  <a href="http://vcg.isti.cnr.it/publication/2020/LPPSC20/" target="_blank" style="margin-right:1rem;">🔗 VCG Page</a>
  <a href="https://github.com/mlivesu/LoopyCuts" target="_blank">💻 Source Code</a>
</div>

**[Marco Livesu](http://vcg.isti.cnr.it/author/Marco-Livesu/)**, **[Nico Pietroni](https://nicopietroni.github.io)**, **[Enrico Puppo](http://vcg.isti.cnr.it/author/Enrico-Puppo/)**, **[Alla Sheffer](http://vcg.isti.cnr.it/author/Alla-Sheffer/)**, **[Paolo Cignoni](http://vcg.isti.cnr.it/author/Paolo-Cignoni/)**

*ACM Transactions on Graphics — Siggraph 2020*

<img src="https://vcgdata.isti.cnr.it/Publications/2020/LPPSC20/teaser.png" style="width:100%;max-width:700px;border-radius:8px;margin:1.5rem 0;">

## Abstract

We present a new fully automatic block-decomposition algorithm for feature-preserving, strongly hex-dominant meshing, that yields results with a drastically larger percentage of hex elements than prior art. Our method is guided by a surface field that conforms to both surface curvature and feature lines, and exploits an ordered set of cutting loops that evenly cover the input surface, defining an arrangement of loops suitable for hex-element generation. We decompose the solid into coarse blocks by iteratively cutting it with surfaces bounded by these loops. The vast majority of the obtained blocks can be turned into hexahedral cells via simple midpoint subdivision.

<img src="https://vcgdata.isti.cnr.it/Publications/2020/LPPSC20/organic_hexa.png" style="width:100%;max-width:700px;border-radius:8px;margin:1.5rem 0;">

<img src="https://vcgdata.isti.cnr.it/Publications/2020/LPPSC20/cad_hexa.png" style="width:100%;max-width:700px;border-radius:8px;margin:1.5rem 0;">
