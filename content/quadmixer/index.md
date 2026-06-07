---
title: QuadMixer
type: page
---

# QuadMixer

## Layout Preserving Blending of Quadrilateral Meshes

<div style="margin:1rem 0;">
  <a href="http://vcg.isti.cnr.it/Publications/2019/NHESCP19/quadmixer_author_version.pdf" target="_blank" style="margin-right:1rem;">📄 Siggraph Paper</a>
  <a href="https://www.dropbox.com/scl/fi/10yu97rqzmds7fkkcgm9a/quadmixer.pptx?rlkey=6bk8cesranngj92u45uvj0e13&st=whlwcs12&dl=0" target="_blank" style="margin-right:1rem;">🎞️ Presentation</a>
  <a href="/publications/quadmixer_results.zip" target="_blank" style="margin-right:1rem;">📦 Dataset</a>
  <a href="https://github.com/stefanonuvoli/quadmixer" target="_blank">💻 Source Code</a>
</div>

**[Stefano Nuvoli](https://github.com/stefanonuvoli)**, **A Hernandez**, **C Esperanca**, **[Riccardo Scateni](https://www.unica.it/unica/page/it/riccardo_scateni)**, **[Paolo Cignoni](http://vcg.isti.cnr.it/~cignoni/)**, **[Nico Pietroni](https://nicopietroni.github.io)**

*ACM Transactions on Graphics — Siggraph Asia 2019*

<img src="/publications/Qmixer_edited.avif" style="width:100%;max-width:700px;border-radius:8px;margin:1.5rem 0;">

## Model-by-Composition

Our modeling principles take inspiration from the classical boolean operations defined on triangle meshes, but with operators redesigned to work on quadrilateral meshes. QuadMixer mimics all the conventional boolean operations that are available for triangle meshes such as union, intersection, and difference.

## A Novel Modelling Approach

QuadMixer is a novel interactive technique to compose quad mesh components preserving the majority of the original layouts. Our technique keeps untouched all the quads in the patches which are not involved in the blending. The resulting mesh preserves the designed edge flow that, by construction, is captured and incorporated to the new quads as much as possible.

<img src="/publications/monkeydolphinunion_edited.avif" style="width:100%;max-width:700px;border-radius:8px;margin:1.5rem 0;">

<img src="/publications/mannequinnalpacaunion_edited.avif" style="width:100%;max-width:700px;border-radius:8px;margin:1.5rem 0;">

## Interactive

QuadMixer works in real-time, allowing the artist to see and adjust the results of the modifications interactively.
