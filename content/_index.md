---
title: ''
summary: ''
date: 2026-01-05
type: landing

sections:
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: ""
      show_status: false
      show_scroll_indicator: true
      typewriter:
        enable: false
      cta_buttons:
        - text: Publications
          url: "#publications"
          icon: arrow-down
        - text: Software
          url: "#software"
          icon: arrow-down
        - text: Artworks
          url: "#artworks"
          icon: arrow-down
        - text: Contact
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: rounded
      animations: false
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]

  - block: markdown
    id: about
    content:
      title: About
      text: |
        My primary research area is Computer Graphics and Geometry Processing, with a focus on developing concepts and practical algorithms for creating and manipulating digital shape representations. My work spans mesh parametrization, surface abstraction and global optimization, with applications in the entertainment industry, digital fabrication, and architectural geometry.
    design:
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: markdown
    id: publications
    content:
      title: Publications
      text: |
        ### SIGGRAPH / ACM Transactions on Graphics

        #### 2025
        <details open>
        <summary><strong>Designing with Tension: Nearly-Developable Patch Layouts</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_designing_with_tensi.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph Asia 2025 — ACM Transactions on Graphics</em><br>
        <span style="font-size:0.9em;color:#888;">A Qi, A Eggler, N Pietroni, P Tang, M Piovarci, B Bickel</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Free-form Surface Approximation Using Rotational Patches</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_free_form_surface_ap.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>ACM Transactions on Graphics, Volume 44, Issue 5</em><br>
        <span style="font-size:0.9em;color:#888;">Y Liu, YM Xie, TU Lee, Z Wang, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Fabricable Discretized Ruled Surface</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_fabricable_discretiz.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph Asia 2025 — ACM Transactions on Graphics, Volume 44, Issue 3</em><br>
        <span style="font-size:0.9em;color:#888;">A Bahrami, M Piovarci, M Tarini, B Bickel, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://doi.org/10.1145/3734519" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Rags2Riches: Computational Garment Reuse</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_rags2riches_computa.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph 2025 — ACM Transactions on Graphics</em><br>
        <span style="font-size:0.9em;color:#888;">A Qi, N Pietroni, M Korosteleva, O Sorkine-Hornung</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://doi.org/10.1145/3641519" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2022
        <details open>
        <summary><strong>SkinMixer: Blending 3D Animated Models</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_skinmixer_blending_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph Asia 2022 — ACM Transactions on Graphics, Volume 41, Issue 6</em><br>
        <span style="font-size:0.9em;color:#888;">S Nuvoli, N Pietroni, R Scateni, P Cignoni, M Tarini</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/3550454.3555503" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="https://www.nicopietroni.com/skinmixer" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Hex-Mesh Generation and Processing: a Survey</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_hex_mesh_generation_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>ACM Transactions on Graphics, Volume 42, Issue 2</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, M Campen, A Sheffer, G Cherchi, D Bommes, X Gao, R Scateni, F Ledoux, JF Remacle, M Livesu</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Computational Pattern Making from 3D Garment Models</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_computational_patter.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph 2022 — ACM Transactions on Graphics, Volume 41, Issue 4</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, C Dumery, R Guenot-Falque, M Liu, T Vidal-Calleja, O Sorkine-Hornung</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/3528223.3530145" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="https://www.nicopietroni.com/parafashion" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2021
        <details open>
        <summary><strong>Volume Decomposition for Two-Piece Rigid Casting</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_volume_decomposition.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph Asia 2021 — ACM Transactions on Graphics, Volume 40, Issue 6</em><br>
        <span style="font-size:0.9em;color:#888;">T Alderighi, L Malomo, B Bickel, P Cignoni, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/3478513.3480555" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2021/AMBCP21/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Reliable Feature-Line Driven Quad-Remeshing</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_reliable_feature_lin.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph 2021 — ACM Transactions on Graphics, Volume 40, Issue 4</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, S Nuvoli, T Alderighi, P Cignoni, M Tarini</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2020
        <details open>
        <summary><strong>LoopyCuts: Practical Feature-Preserving Block Decomposition</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_loopycuts_practical.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph 2020 — ACM Transactions on Graphics, Volume 39, Issue 4</em><br>
        <span style="font-size:0.9em;color:#888;">M Livesu*, N Pietroni*, E Puppo, A Sheffer, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/3386569.3392472" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2020/LPPSC20/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Reinforcement of General Shell Structures</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_reinforcement_of_gen.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>ACM Transactions on Graphics, June 2020</em><br>
        <span style="font-size:0.9em;color:#888;">FT Gil Ureta, N Pietroni, D Zorin</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/3375677" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2020/GPZ20/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2019
        <details open>
        <summary><strong>QuadMixer: Layout Preserving Blending of Quadrilateral Meshes</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_quadmixer_layout_pr.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph Asia 2019 — ACM Transactions on Graphics, Volume 38, Issue 6</em><br>
        <span style="font-size:0.9em;color:#888;">S Nuvoli, A Hernandez, C Esperanca, R Scateni, P Cignoni, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/3355089.3356542" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="https://www.nicopietroni.com/quadmixer" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Volume-Aware Design of Composite Molds</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_volume_aware_design_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph 2019 — ACM Transactions on Graphics, Volume 38, Issue 4</em><br>
        <span style="font-size:0.9em;color:#888;">T Alderighi, L Malomo, D Giorgi, B Bickel, P Cignoni, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2018
        <details open>
        <summary><strong>FlexMaps: Computational Design of Flat Flexible Shells for Shaping 3D Objects</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_flexmaps_computatio.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph Asia 2018 — ACM Transactions on Graphics, Volume 37, Issue 6</em><br>
        <span style="font-size:0.9em;color:#888;">L Malomo, J Pérez, E Iarussi, N Pietroni, E Miguel, P Cignoni, B Bickel</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/3272127.3275076" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2018/MPIPMCB18/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Metamolds: Computational Design of Silicone Molds</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_metamolds_computati.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph 2018 — ACM Transactions on Graphics, Volume 37, Issue 4</em><br>
        <span style="font-size:0.9em;color:#888;">T Alderighi, L Malomo, D Giorgi, N Pietroni, B Bickel, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/3197517.3201381" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2018/AMGPBC18/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2017
        <details open>
        <summary><strong>Position Based Tensegrity Design</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_position_based_tense.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph Asia 2017 — ACM Transactions on Graphics, Volume 36, Issue 6</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, M Tarini, A Vaxman, D Panozzo, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/3130800.3130809" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2017/PTVPC17/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2016
        <details open>
        <summary><strong>FlexMolds: Automatic Design of Flexible Shells for Molding</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_flexmolds_automatic.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph Asia 2016 — ACM Transactions on Graphics, Volume 35, Issue 6</em><br>
        <span style="font-size:0.9em;color:#888;">L Malomo, N Pietroni, B Bickel, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/2980179.2982397" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2016/MPBC16/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2015
        <details open>
        <summary><strong>Data-Driven Interactive Quadrangulation</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_data_driven_interact.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph 2015 — ACM Transactions on Graphics, Volume 34, Issue 65</em><br>
        <span style="font-size:0.9em;color:#888;">G Marcias, K Takayama, N Pietroni, D Panozzo, O Sorkine-Hornung, E Puppo, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Elastic Textures for Additive Fabrication</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_elastic_textures_for.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph 2015 — ACM Transactions on Graphics, Volume 34, Issue 4</em><br>
        <span style="font-size:0.9em;color:#888;">J Panetta, Q Zhou, L Malomo, N Pietroni, P Cignoni, D Zorin</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/2766937" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2015/PZMPCZ15/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2014
        <details open>
        <summary><strong>Robust Field-Aligned Global Parametrization</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_robust_field_aligned.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph 2014 — ACM Transactions on Graphics, Volume 33, Issue 4</em><br>
        <span style="font-size:0.9em;color:#888;">A Myles, N Pietroni, D Zorin</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Field-Aligned Mesh Joinery</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_field_aligned_mesh_j.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph Asia 2014 — ACM Transactions on Graphics, Volume 33, Issue 1</em><br>
        <span style="font-size:0.9em;color:#888;">P Cignoni, N Pietroni, L Malomo, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2011
        <details open>
        <summary><strong>Simple Quad Domains for Field Aligned Mesh Parametrization</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_simple_quad_domains_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph Asia 2011 — ACM Transactions on Graphics, Volume 30, Issue 6</em><br>
        <span style="font-size:0.9em;color:#888;">M Tarini, E Puppo, D Panozzo, N Pietroni, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/2070781.2024176" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2011/TPPPC11/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Global Parametrization of Range Image Sets</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_global_parametrizati.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph Asia 2011 — ACM Transactions on Graphics, Volume 30, Issue 6</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, M Tarini, O Sorkine, D Zorin</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://dl.acm.org/doi/10.1145/2070781.2024183" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2011/PTSZ11/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2010
        <details open>
        <summary><strong>Feature-Aligned T-Meshes</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_feature_aligned_t_me.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Siggraph 2010 — ACM Transactions on Graphics, Volume 29, Issue 4</em><br>
        <span style="font-size:0.9em;color:#888;">A Myles, N Pietroni, D Kovacs, D Zorin</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        ---

        ### Other Journal Publications

        #### 2024
        <details open>
        <summary><strong>Digital Garment Alteration</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_digital_garment_alte.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, Volume 43, Issue 7 — Pacific Graphics 2024</em><br>
        <span style="font-size:0.9em;color:#888;">A Eggler, R Falque, M Liu, T Vidal-Calleja, O Sorkine-Hornung, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://doi.org/10.1111/cgf.15248" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Bending-Reinforced Grid Shells for Free-form Architectural Surfaces</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_bending_reinforced_g.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer-Aided Design, Volume 168 — 2024</em><br>
        <span style="font-size:0.9em;color:#888;">F Laccone, N Pietroni, P Cignoni, L Malomo</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Automated Shotcrete: A More Sustainable Construction Technology</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_automated_shotcrete.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Sustainable Engineering: Concepts and Practices — 2024</em><br>
        <span style="font-size:0.9em;color:#888;">G Isaac, P Nicholas, G Paul, N Pietroni, T Vidal Calleja, M Xie, T Schork</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Design and Construction of Catenary-Ruled Surfaces</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_design_and_construct.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Structures, Volume 59 — 2024</em><br>
        <span style="font-size:0.9em;color:#888;">Z Li, TU Lee, N Pietroni, R Snooks, YM Xie</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Reducing the Number of Different Faces in Free-Form Surface Approximations</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_reducing_the_number_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer-Aided Design, Volume 166 — 2024</em><br>
        <span style="font-size:0.9em;color:#888;">Y Liu, TU Lee, AR Javan, N Pietroni, YM Xie</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2023
        <details open>
        <summary><strong>Bending the Light: Next Generation Anamorphic Sculptures</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_bending_the_light_n.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computers & Graphics, SMI 2023</em><br>
        <span style="font-size:0.9em;color:#888;">L Pratt, A Johnston, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://doi.org/10.1016/j.cag.2023.05.023" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="https://www.nicopietroni.com/bendingthelight" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>HexBox: Interactive Box Modeling of Hexahedral Meshes</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_hexbox_interactive_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, SGP 2023</em><br>
        <span style="font-size:0.9em;color:#888;">F Zoccheddu, E Gobetti, M Livesu, N Pietroni, YM Xie</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Physically-based Simulation of Elastic-Plastic Fusion of 3D Bioprinted Spheroids</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_physically_based_sim.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Biofabrication, Volume 15, Issue 4 — 2023</em><br>
        <span style="font-size:0.9em;color:#888;">H Bahrami, F Sichetti, E Puppo, L Vettori, C Liu, S Perry, C Gentile, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Reflections on Light: Developing New Methods for Producing Anamorphic Sculpture</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_reflections_on_light.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>MIT Leonardo, 56(6) — 2023</em><br>
        <span style="font-size:0.9em;color:#888;">L Pratt, A Johnstone, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Reducing the Number of Different Nodes in Space Frame Structures</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_reducing_the_number_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Engineering Structures, Volume 284 — 2023</em><br>
        <span style="font-size:0.9em;color:#888;">Y Liu, TU Lee, A Koronaki, N Pietroni, YM Xie</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2022
        <details open>
        <summary><strong>State of the Art in Computational Mould Design</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_state_of_the_art_in_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, Volume 41, Issue 6 — 2022</em><br>
        <span style="font-size:0.9em;color:#888;">T Alderighi, L Malomo, T Auzinger, B Bickel, P Cignoni, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Design and Construction of a Bending-Active Plywood Structure: The Flexmaps Pavilion</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_design_and_construct.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Journal of the IASS, Volume 63, Issue 2 — 2022</em><br>
        <span style="font-size:0.9em;color:#888;">F Laccone, L Malomo, M Callieri, T Alderighi, A Muntoni, F Ponchio, N Pietroni, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2021
        <details open>
        <summary><strong>Integrated Computational Framework for the Design and Fabrication of Bending-Active Structures</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_integrated_computati.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Structures, Volume 34 — 2021</em><br>
        <span style="font-size:0.9em;color:#888;">F Laccone, L Malomo, N Pietroni, P Cignoni, T Schork</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Automatic Surface Segmentation for Seamless Fabrication Using 4-Axis Milling Machines</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_automatic_surface_se.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, Eurographics 2021</em><br>
        <span style="font-size:0.9em;color:#888;">S Nuvoli, A Tola, A Muntoni, N Pietroni, E Gobbetti, R Scateni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://doi.org/10.1111/cgf.142625" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="https://www.crs4.it/vic/cgi-bin/bib-page.cgi?id='Nuvoli:2021:ASS'" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2020
        <details open>
        <summary><strong>Skeleton-Based Conditionally Independent Gaussian Process Implicit Surfaces</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_skeleton_based_condi.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>IEEE Robotics and Automation Letters, Volume 5, Issue 2 — 2020</em><br>
        <span style="font-size:0.9em;color:#888;">L Wu, R Falque, V Perez-Puchalt, L Liu, N Pietroni, T Vidal-Calleja</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Automatic Design of Cable-Tensioned Glass Shells</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_automatic_design_of_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, Volume 39, Issue 1 — 2020</em><br>
        <span style="font-size:0.9em;color:#888;">F Laccone, L Malomo, M Froli, P Cignoni, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>A Bending-Active Twisted-Arch Plywood Structure: The FlexMaps Pavilion</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_a_bending_active_twi.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>SN Applied Sciences, Volume 2 — 2020</em><br>
        <span style="font-size:0.9em;color:#888;">F Laccone, L Malomo, J Pérez, N Pietroni, F Ponchio, B Bickel, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2019
        <details open>
        <summary><strong>HexaLab.net: An Online Viewer for Hexahedral Meshes</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_hexalab.net_an_onli.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer-Aided Design, Volume 110 — 2019</em><br>
        <span style="font-size:0.9em;color:#888;">M Bracci, M Tarini, N Pietroni, M Livesu, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
                <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2018
        <details open>
        <summary><strong>State of the Art on Stylized Fabrication</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_state_of_the_art_on_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, Volume 37, Issue 6 — 2018</em><br>
        <span style="font-size:0.9em;color:#888;">B Bickel, P Cignoni, L Malomo, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2017
        <details open>
        <summary><strong>Digital Fabrication Techniques for Cultural Heritage: A Survey</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_digital_fabrication_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, Volume 36, Issue 1 — 2017</em><br>
        <span style="font-size:0.9em;color:#888;">R Scopigno, P Cignoni, N Pietroni, M Callieri, M Dellepiane</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2016
        <details open>
        <summary><strong>Tracing Field-Coherent Quad Layouts</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_tracing_field_cohere.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, Pacific Graphics 2016</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, E Puppo, G Marcias, R Scopigno, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Stability of Statics Aware Voronoi Grid-Shells</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_stability_of_statics.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Engineering Structures, Volume 116 — 2016</em><br>
        <span style="font-size:0.9em;color:#888;">D Tonelli, N Pietroni, E Puppo, M Froli, P Cignoni, G Amendola, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2015
        <details open>
        <summary><strong>Statics Aware Grid Shells</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_statics_aware_grid_s.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, Eurographics 2015</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, D Tonelli, E Puppo, M Froli, R Scopigno, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://doi.org/10.1111/cgf.12590" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2015/PTPFSC15/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Compression and Querying of Arbitrary Geodesic Distances</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_compression_and_quer.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Lecture Notes in Computer Science, Volume 9279 — 2015</em><br>
        <span style="font-size:0.9em;color:#888;">R Aiello, F Banterle, N Pietroni, L Malomo, P Cignoni, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2013
        <details open>
        <summary><strong>Animation-Aware Quadrangulation</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_animation_aware_quad.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, SGP 2013</em><br>
        <span style="font-size:0.9em;color:#888;">G Marcias, N Pietroni, D Panozzo, E Puppo, O Sorkine</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Quad-Mesh Generation and Processing: A Survey</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_quad_mesh_generation.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum — 2013</em><br>
        <span style="font-size:0.9em;color:#888;">D Bommes, B Lévy, N Pietroni, E Puppo, C Silva, M Tarini, D Zorin</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2011
        <details open>
        <summary><strong>An Interactive Local Flattening Operator to Support Digital Investigations on Artwork Surfaces</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_an_interactive_local.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>IEEE Transactions on Visualization and Computer Graphics — IEEE Visualization 2011</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, M Corsini, P Cignoni, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://doi.org/10.1109/TVCG.2011.165" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2011/PCCS11/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Automatic Construction of Adaptive Quad-Based Subdivision Surfaces Using Fitmaps</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_automatic_constructi.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>IEEE Transactions on Visualization and Computer Graphics, Volume 17, Issue 10 — 2011</em><br>
        <span style="font-size:0.9em;color:#888;">D Panozzo, E Puppo, M Tarini, N Pietroni, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="https://doi.org/10.1109/TVCG.2011.28" target="_blank" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="http://vcg.isti.cnr.it/Publications/2011/PPTPC11/" target="_blank">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2010
        <details open>
        <summary><strong>Almost Isometric Mesh Parameterization Through Abstract Domains</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_almost_isometric_mes.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>IEEE Transactions on Visualization and Computer Graphics, Volume 16, Issue 4 — 2010</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, M Tarini, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Practical Quad Mesh Simplification</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_practical_quad_mesh_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, Eurographics 2010</em><br>
        <span style="font-size:0.9em;color:#888;">M Tarini, N Pietroni, P Cignoni, D Panozzo, E Puppo</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Real-time Single Scattering Inside Inhomogeneous Materials</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_real_time_single_sca.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>The Visual Computer, CGI 2010</em><br>
        <span style="font-size:0.9em;color:#888;">D Bernabei, F Ganovelli, N Pietroni, P Cignoni, S Pattanaik, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Solid-Texture Synthesis: A Survey</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_solid_texture_synthe.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>IEEE Computer Graphics and Applications, Volume 30, Issue 4 — 2010</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, P Cignoni, MA Otaduy, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2009
        <details open>
        <summary><strong>Splitting Cubes: A Fast and Robust Technique for Virtual Cutting</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_splitting_cubes_a_f.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>The Visual Computer, Volume 25, Issue 3 — 2009</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, F Ganovelli, P Cignoni, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2008
        <details open>
        <summary><strong>Reconstructing Head Models from Photographs for Individualized 3D-Audio Processing</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_reconstructing_head_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, Pacific Graphics 2008</em><br>
        <span style="font-size:0.9em;color:#888;">M Dellepiane, N Pietroni, N Tsingos, M Asselot, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2007
        <details open>
        <summary><strong>Texturing Internal Surfaces from a Few Cross Sections</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_texturing_internal_s.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Computer Graphics Forum, Eurographics 2007</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, MA Otaduy, B Bickel, F Ganovelli, MH Gross</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        [Full list on Google Scholar](https://scholar.google.it/citations?user=BXxHVPkAAAAJ&hl=en)

        ---

        ### Conference Publications

        #### 2023
        <details open>
        <summary><strong>Statics and Stability of Bending-Optimized Double-Layer Grid Shell</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_statics_and_stabilit.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Italian Workshop on Shell and Spatial Structures — 2023</em><br>
        <span style="font-size:0.9em;color:#888;">F Laccone, N Pietroni, M Froli, P Cignoni, L Malomo</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>A Neural Network-based Low-cost Soft Sensor for Touch Recognition and Deformation Capture</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_a_neural_network_bas.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>ACM Designing Interactive Systems — 2023</em><br>
        <span style="font-size:0.9em;color:#888;">Y Fan, N Pietroni, S Ferguson</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2020
        <details open>
        <summary><strong>Automated Design and Analysis of Reinforced and Post-Tensioned Glass Shells</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_automated_design_and.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Challenging Glass Conference — 2020</em><br>
        <span style="font-size:0.9em;color:#888;">F Laccone, L Malomo, N Pietroni, M Froli, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2019
        <details open>
        <summary><strong>FlexMaps Pavilion: A Twisted Arc Made of Mesostructured Flat Flexible Panels</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_flexmaps_pavilion_a_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>IASS 2019: FORM and FORCE</em><br>
        <span style="font-size:0.9em;color:#888;">F Laccone, L Malomo, J Perez, N Pietroni, F Ponchio, B Bickel, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Concept and Cable-Tensioning Optimization of Post-Tensioned Shells Made of Structural Glass</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_concept_and_cable_te.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>IASS 2019: FORM and FORCE</em><br>
        <span style="font-size:0.9em;color:#888;">F Laccone, L Malomo, M Froli, P Cignoni, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2016
        <details open>
        <summary><strong>Design and Fabrication of Grid-shells Mockups</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_design_and_fabricati.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>STAG: Smart Tools and Apps for Graphics — 2016</em><br>
        <span style="font-size:0.9em;color:#888;">D Tonelli, N Pietroni, P Cignoni, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>State Of The Art on Functional Fabrication</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_state_of_the_art_on_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Eurographics Workshop on Graphics for Digital Fabrication — 2016</em><br>
        <span style="font-size:0.9em;color:#888;">A Medeiros e Sá, K Rodriguez Echavarria, N Pietroni, P Cignoni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2014
        <details open>
        <summary><strong>Digital Fabrication Technologies for Cultural Heritage (STAR)</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_digital_fabrication_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Eurographics Workshops on Graphics and Cultural Heritage — 2014</em><br>
        <span style="font-size:0.9em;color:#888;">R Scopigno, P Cignoni, N Pietroni, M Callieri, M Dellepiane</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Interlocking Pieces for Printing Tangible Cultural Heritage Replicas</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_interlocking_pieces_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Eurographics Workshops on Graphics and Cultural Heritage — 2014</em><br>
        <span style="font-size:0.9em;color:#888;">G Alemanno, P Cignoni, N Pietroni, F Ponchio, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2013
        <details open>
        <summary><strong>A Computer-Assisted Constraint-Based System for Assembling Fragmented Objects</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_a_computer_assisted_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>IEEE Digital Heritage — 2013</em><br>
        <span style="font-size:0.9em;color:#888;">G Palmas, N Pietroni, P Cignoni, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2010
        <details open>
        <summary><strong>Adaptive Quad Mesh Simplification</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_adaptive_quad_mesh_s.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Eurographics Italian Chapter — 2010</em><br>
        <span style="font-size:0.9em;color:#888;">A Bozzo, D Panozzo, E Puppo, N Pietroni, L Rocca</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2007
        <details open>
        <summary><strong>Techniques for Computer Assisted Surgery</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_techniques_for_compu.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Eurographics Italian Chapter — 2007</em><br>
        <span style="font-size:0.9em;color:#888;">G Turini, N Pietroni, F Ganovelli, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>A Robust Method for Real-Time Thread Simulation</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_a_robust_method_for_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>ACM VRST 2007</em><br>
        <span style="font-size:0.9em;color:#888;">B Kubiak, N Pietroni, F Ganovelli, M Fratarcangeli</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        #### 2005
        <details open>
        <summary><strong>Robust Segmentation of Anatomical Structures with Deformable Surfaces and Marching Cubes</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_robust_segmentation_.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>VRIPHYS 2005</em><br>
        <span style="font-size:0.9em;color:#888;">N Pietroni, A Giachetti, F Ganovelli</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>

        ---

        ### Patents
        <details open>
        <summary><strong>Method for Computationally Designing a Re-usable Flexible Mold</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_patent_flexmold_eu.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>European Patent EP3301597B1</em><br>
        <span style="font-size:0.9em;color:#888;">P Cignoni, N Pietroni, L Malomo, B Bickel</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Method for Computationally Designing a Re-usable Flexible Mold for the Reproduction of an Object</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_patent_flexmold_us.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>US Patent US11966666B2</em><br>
        <span style="font-size:0.9em;color:#888;">T Alderighi, P Cignoni, L Malomo, D Giorgi, B Bickel, N Pietroni</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
        <details open>
        <summary><strong>Mesh Joinery: Method for Converting a 3D Model into a Set of Planar Shapes</strong></summary>
        <div style="display:flex;gap:1rem;margin-top:0.5rem;align-items:flex-start;">
        <img src="/publications/pub_patent_mesh_joinery.jpg" onerror="this.src='https://placehold.co/120x80/444444/888888?text=img'" style="width:120px;height:80px;object-fit:cover;border-radius:4px;flex-shrink:0;">
        <div>
        <em>Italian Patent ITRM20130439A1 — 2013</em><br>
        <span style="font-size:0.9em;color:#888;">P Cignoni, N Pietroni, L Malomo, R Scopigno</span><br>
        <span style="margin-top:0.4rem;display:inline-block;">
        <a href="#" style="margin-right:0.8rem;">📄 PDF</a>
        <a href="#">🔗 Project Page</a>
        </span>
        </div>
        </div>
        </details>
    design:
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]


  - block: markdown
    id: software
    content:
      title: Software
      text: |
        <div style="display:grid;grid-template-columns:repeat(auto-fill,minmax(280px,1fr));gap:2rem;margin-top:1rem;">

        <div style="text-align:center;">
        <a href="https://www.meshlab.net" target="_blank">
        <img src="/publications/pub_software_meshlab.jpg" style="width:100%;height:200px;object-fit:cover;border-radius:8px;display:block;">
        <p style="margin-top:0.5rem;font-weight:bold;font-size:1.1em;">MeshLab</p>
        </a>
        <p style="font-size:0.9em;color:#888;">Open source system for processing and editing 3D triangular meshes. Over 3 million downloads worldwide.</p>
        </div>

        <div style="text-align:center;">
        <a href="https://www.hexalab.net" target="_blank">
        <img src="/publications/pub_software_hexalab.jpg" style="width:100%;height:200px;object-fit:cover;border-radius:8px;display:block;">
        <p style="margin-top:0.5rem;font-weight:bold;font-size:1.1em;">HexaLab</p>
        </a>
        <p style="font-size:0.9em;color:#888;">Online WebGL viewer for hexahedral meshes, used as standard tool in academia for volumetric mesh visualization.</p>
        </div>

        <div style="text-align:center;">
        <a href="https://github.com/mlivesu/LoopyCuts" target="_blank">
        <img src="/publications/pub_software_loopycuts.jpg" style="width:100%;height:200px;object-fit:cover;border-radius:8px;display:block;">
        <p style="margin-top:0.5rem;font-weight:bold;font-size:1.1em;">LoopyCuts</p>
        </a>
        <p style="font-size:0.9em;color:#888;">Practical feature-preserving block decomposition for strongly hex-dominant meshing.</p>
        </div>

        <div style="text-align:center;">
        <a href="https://www.nicopietroni.com/quadmixer" target="_blank">
        <img src="/publications/pub_software_quadmixer.jpg" style="width:100%;height:200px;object-fit:cover;border-radius:8px;display:block;">
        <p style="margin-top:0.5rem;font-weight:bold;font-size:1.1em;">QuadMixer</p>
        </a>
        <p style="font-size:0.9em;color:#888;">Layout preserving blending of quadrilateral meshes for 3D modelling and animation.</p>
        </div>

        <div style="text-align:center;">
        <a href="https://github.com/nicopietroni/quadwild" target="_blank">
        <img src="/publications/pub_software_quadwild.jpg" style="width:100%;height:200px;object-fit:cover;border-radius:8px;display:block;">
        <p style="margin-top:0.5rem;font-weight:bold;font-size:1.1em;">QuadWild</p>
        </a>
        <p style="font-size:0.9em;color:#888;">Robust field-aligned global parametrization and quad mesh generation.</p>
        </div>

        <div style="text-align:center;">
        <a href="https://www.nicopietroni.com/parafashion" target="_blank">
        <img src="/publications/pub_software_parafashion.jpg" style="width:100%;height:200px;object-fit:cover;border-radius:8px;display:block;">
        <p style="margin-top:0.5rem;font-weight:bold;font-size:1.1em;">Parafashion</p>
        </a>
        <p style="font-size:0.9em;color:#888;">Computational pattern making from 3D garment models for digital fashion design.</p>
        </div>

        </div>
    design:
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: markdown
    id: artworks
    content:
      title: Artworks & Installations
      text: |
        My research has led to art installations and exhibitions combining geometry processing and art.

        - **Galleria Gagliardi 2025** — *A Very Dutch Ghost*
        - **Sydney Contemporary 2024** — Lennox St Gallery
        - **North Sydney Art Prize 2024** — Finalist
        - **Wynne Prize 2023** — Finalist, Art Gallery of New South Wales *(selected 40 out of ~800 submissions)*
        - **Sydney Contemporary 2022** — Nanda/Hobbs Gallery
        - **Fisher's Ghost Art Prize 2022** — Finalist
        - **Venice Biennale of Architecture 2021** — *FlexMaps Pavilion*
        - **Nerves of Steel 2017** — Permanent Sculpture, CNR of Italy
    design:
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]

  - block: contact-info
    id: contact
    content:
      title: Contact
      text: |
        Building 11, University of Technology Sydney
        81 Broadway, Ultimo NSW 2007, Australia
      email: nico.pietroni@uts.edu.au
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "6rem", "0"]
---
