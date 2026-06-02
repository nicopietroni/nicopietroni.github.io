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
        - text: Artworks
          url: "#artworks"
          icon: arrow-down
        - text: Contact
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: circle
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

        <details>
        <summary><strong>Designing with Tension: Nearly-Developable Patch Layouts</strong> — <em>Siggraph Asia 2025</em></summary>
        A Qi, A Eggler, N Pietroni, P Tang, M Piovarci, B Bickel
        </details>

        <details>
        <summary><strong>Free-form Surface Approximation Using Rotational Patches</strong> — <em>ACM TOG 2025</em></summary>
        Y Liu, YM Xie, TU Lee, Z Wang, N Pietroni
        </details>

        <details>
        <summary><strong>Fabricable Discretized Ruled Surface</strong> — <em>Siggraph Asia 2025</em></summary>
        A Bahrami, M Piovarci, M Tarini, B Bickel, N Pietroni
        </details>

        <details>
        <summary><strong>Rags2Riches: Computational Garment Reuse</strong> — <em>Siggraph 2025</em></summary>
        A Qi, N Pietroni, M Korosteleva, O Sorkine-Hornung
        </details>

        <details>
        <summary><strong>SkinMixer: Blending 3D Animated Models</strong> — <em>Siggraph Asia 2022</em></summary>
        S Nuvoli, N Pietroni, R Scateni, P Cignoni, M Tarini
        </details>

        <details>
        <summary><strong>Hex-Mesh Generation and Processing: a Survey</strong> — <em>ACM TOG 2022</em></summary>
        N Pietroni, M Campen, A Sheffer, G Cherchi, D Bommes et al.
        </details>

        <details>
        <summary><strong>Computational Pattern Making from 3D Garment Models</strong> — <em>Siggraph 2022</em></summary>
        N Pietroni, C Dumery, R Guenot-Falque, M Liu, T Vidal-Calleja, O Sorkine-Hornung
        </details>

        <details>
        <summary><strong>Volume Decomposition for Two-Piece Rigid Casting</strong> — <em>Siggraph Asia 2021</em></summary>
        T Alderighi, L Malomo, B Bickel, P Cignoni, N Pietroni
        </details>

        <details>
        <summary><strong>Reliable Feature-Line Driven Quad-Remeshing</strong> — <em>Siggraph 2021</em></summary>
        N Pietroni, S Nuvoli, T Alderighi, P Cignoni, M Tarini
        </details>

        <details>
        <summary><strong>LoopyCuts: Practical Feature-Preserving Block Decomposition</strong> — <em>Siggraph 2020</em></summary>
        M Livesu*, N Pietroni*, E Puppo, A Sheffer, P Cignoni
        </details>

        <details>
        <summary><strong>Reinforcement of General Shell Structures</strong> — <em>ACM TOG 2020</em></summary>
        FT Gil Ureta, N Pietroni, D Zorin
        </details>

        <details>
        <summary><strong>QuadMixer: Layout Preserving Blending of Quadrilateral Meshes</strong> — <em>Siggraph Asia 2019</em></summary>
        S Nuvoli, A Hernandez, C Esperanca, R Scateni, P Cignoni, N Pietroni
        </details>

        <details>
        <summary><strong>Volume-Aware Design of Composite Molds</strong> — <em>Siggraph 2019</em></summary>
        T Alderighi, L Malomo, D Giorgi, B Bickel, P Cignoni, N Pietroni
        </details>

        <details>
        <summary><strong>FlexMaps: Computational Design of Flat Flexible Shells</strong> — <em>Siggraph Asia 2018</em></summary>
        L Malomo, J Pérez, E Iarussi, N Pietroni, E Miguel, P Cignoni, B Bickel
        </details>

        <details>
        <summary><strong>Metamolds: Computational Design of Silicone Molds</strong> — <em>Siggraph 2018</em></summary>
        T Alderighi, L Malomo, D Giorgi, N Pietroni, B Bickel, P Cignoni
        </details>

        <details>
        <summary><strong>Position Based Tensegrity Design</strong> — <em>Siggraph Asia 2017</em></summary>
        N Pietroni, M Tarini, A Vaxman, D Panozzo, P Cignoni
        </details>

        <details>
        <summary><strong>FlexMolds: Automatic Design of Flexible Shells for Molding</strong> — <em>Siggraph Asia 2016</em></summary>
        L Malomo, N Pietroni, B Bickel, P Cignoni
        </details>

        <details>
        <summary><strong>Data-Driven Interactive Quadrangulation</strong> — <em>Siggraph 2015</em></summary>
        G Marcias, K Takayama, N Pietroni, D Panozzo, O Sorkine-Hornung, E Puppo, P Cignoni
        </details>

        <details>
        <summary><strong>Elastic Textures for Additive Fabrication</strong> — <em>Siggraph 2015</em></summary>
        J Panetta, Q Zhou, L Malomo, N Pietroni, P Cignoni, D Zorin
        </details>

        <details>
        <summary><strong>Robust Field-Aligned Global Parametrization</strong> — <em>Siggraph 2014</em></summary>
        A Myles, N Pietroni, D Zorin
        </details>

        <details>
        <summary><strong>Field-Aligned Mesh Joinery</strong> — <em>Siggraph Asia 2014</em></summary>
        P Cignoni, N Pietroni, L Malomo, R Scopigno
        </details>

        <details>
        <summary><strong>Simple Quad Domains for Field Aligned Mesh Parametrization</strong> — <em>Siggraph Asia 2011</em></summary>
        M Tarini, E Puppo, D Panozzo, N Pietroni, P Cignoni
        </details>

        <details>
        <summary><strong>Global Parametrization of Range Image Sets</strong> — <em>Siggraph Asia 2011</em></summary>
        N Pietroni, M Tarini, O Sorkine, D Zorin
        </details>

        <details>
        <summary><strong>Feature-Aligned T-Meshes</strong> — <em>Siggraph 2010</em></summary>
        A Myles, N Pietroni, D Kovacs, D Zorin
        </details>

        ---

        ### Other Journal Publications

        <details>
        <summary><strong>Digital Garment Alteration</strong> — <em>Computer Graphics Forum, Pacific Graphics 2024</em></summary>
        A Eggler, R Falque, M Liu, T Vidal-Calleja, O Sorkine-Hornung, N Pietroni
        </details>

        <details>
        <summary><strong>Bending the Light: Next Generation Anamorphic Sculptures</strong> — <em>Computers & Graphics 2023</em></summary>
        L Pratt, A Johnston, N Pietroni
        </details>

        <details>
        <summary><strong>HexBox: Interactive Box Modeling of Hexahedral Meshes</strong> — <em>CGF SGP 2023</em></summary>
        F Zoccheddu, E Gobetti, M Livesu, N Pietroni, YM Xie
        </details>

        <details>
        <summary><strong>State of the Art in Computational Mould Design</strong> — <em>Computer Graphics Forum 2022</em></summary>
        T Alderighi, L Malomo, T Auzinger, B Bickel, P Cignoni, N Pietroni
        </details>

        <details>
        <summary><strong>Automatic Surface Segmentation for Seamless Fabrication</strong> — <em>Eurographics 2021</em></summary>
        S Nuvoli, A Tola, A Muntoni, N Pietroni, E Gobbetti, R Scateni
        </details>

        <details>
        <summary><strong>Automatic Design of Cable-Tensioned Glass Shells</strong> — <em>Computer Graphics Forum 2020</em></summary>
        F Laccone, L Malomo, M Froli, P Cignoni, N Pietroni
        </details>

        <details>
        <summary><strong>HexaLab.net: An Online Viewer for Hexahedral Meshes</strong> — <em>Computer-Aided Design 2019</em></summary>
        M Bracci, M Tarini, N Pietroni, M Livesu, P Cignoni
        </details>

        <details>
        <summary><strong>State of the Art on Stylized Fabrication</strong> — <em>Computer Graphics Forum 2018</em></summary>
        B Bickel, P Cignoni, L Malomo, N Pietroni
        </details>

        <details>
        <summary><strong>Tracing Field-Coherent Quad Layouts</strong> — <em>Pacific Graphics 2016</em></summary>
        N Pietroni, E Puppo, G Marcias, R Scopigno, P Cignoni
        </details>

        <details>
        <summary><strong>Statics Aware Grid Shells</strong> — <em>Eurographics 2015</em></summary>
        N Pietroni, D Tonelli, E Puppo, M Froli, R Scopigno, P Cignoni
        </details>

        <details>
        <summary><strong>Quad-Mesh Generation and Processing: A Survey</strong> — <em>Computer Graphics Forum 2013</em></summary>
        D Bommes, B Lévy, N Pietroni, E Puppo, C Silva, M Tarini, D Zorin
        </details>

        <details>
        <summary><strong>Animation-Aware Quadrangulation</strong> — <em>SGP 2013</em></summary>
        G Marcias, N Pietroni, D Panozzo, E Puppo, O Sorkine
        </details>

        <details>
        <summary><strong>Almost Isometric Mesh Parameterization Through Abstract Domains</strong> — <em>IEEE TVCG 2010</em></summary>
        N Pietroni, M Tarini, P Cignoni
        </details>

        [Full list on Google Scholar](https://scholar.google.it/citations?user=BXxHVPkAAAAJ&hl=en)
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
