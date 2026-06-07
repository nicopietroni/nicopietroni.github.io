---
title: QuadMixer
type: page
---

# QuadMixer

## Layout Preserving Blending of Quadrilateral Meshes

<div style="margin:1.5rem 0;">
  <iframe width="700" height="394" src="https://www.youtube.com/embed/mOgC8lFE6tI" frameborder="0" allowfullscreen style="max-width:100%;border-radius:8px;"></iframe>
</div>

<div style="margin:1rem 0 2rem 0;">
  <a href="http://vcg.isti.cnr.it/Publications/2019/NHESCP19/quadmixer_author_version.pdf" target="_blank" style="margin-right:1rem;">📄 Siggraph Paper</a>
  <a href="https://www.dropbox.com/scl/fi/10yu97rqzmds7fkkcgm9a/quadmixer.pptx?rlkey=6bk8cesranngj92u45uvj0e13&st=whlwcs12&dl=0" target="_blank" style="margin-right:1rem;">🎞️ Presentation</a>
  <a href="/publications/quadmixer_results.zip" target="_blank" style="margin-right:1rem;">📦 Dataset</a>
  <a href="https://github.com/stefanonuvoli/quadmixer" target="_blank">💻 Source Code</a>
</div>

**[Stefano Nuvoli](https://github.com/stefanonuvoli)**, **A Hernandez**, **C Esperanca**, **[Riccardo Scateni](https://www.unica.it/unica/page/it/riccardo_scateni)**, **[Paolo Cignoni](http://vcg.isti.cnr.it/~cignoni/)**, **[Nico Pietroni](https://nicopietroni.github.io)**

*ACM Transactions on Graphics — Siggraph Asia 2019*

---

## Model-by-Composition

<div style="display:flex;gap:2rem;align-items:flex-start;margin:1.5rem 0;">
  <img src="/publications/Qmixer_edited.avif" style="width:320px;border-radius:8px;flex-shrink:0;">
  <div>
    Our modeling principles take inspiration from the classical boolean operations defined on triangle meshes, but with operators redesigned to work on quadrilateral meshes. QuadMixer mimics all the conventional boolean operations that are available for triangle meshes such as union, intersection, and difference.
  </div>
</div>

## A Novel Modelling Approach

<div style="display:flex;gap:2rem;align-items:flex-start;margin:1.5rem 0;">
  <img src="/publications/monkeydolphinunion_edited.avif" style="width:320px;border-radius:8px;flex-shrink:0;">
  <div>
    QuadMixer is a novel interactive technique to compose quad mesh components preserving the majority of the original layouts. Our technique keeps untouched all the quads in the patches which are not involved in the blending. The resulting mesh preserves the designed edge flow that, by construction, is captured and incorporated to the new quads as much as possible.
  </div>
</div>

## Interactive

<div style="display:flex;gap:2rem;align-items:flex-start;margin:1.5rem 0;">
  <img src="/publications/mannequinnalpacaunion_edited.avif" style="width:320px;border-radius:8px;flex-shrink:0;">
  <div>
    QuadMixer works in real-time, allowing the artist to see and adjust the results of the modifications interactively.
  </div>
</div>
