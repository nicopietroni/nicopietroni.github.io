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

        **Designing with Tension: Nearly-Developable Patch Layouts**
        A Qi, A Eggler, N Pietroni, P Tang, M Piovarci, B Bickel — *Siggraph Asia 2025*

        **Free-form Surface Approximation Using Rotational Patches**
        Y Liu, YM Xie, TU Lee, Z Wang, N Pietroni — *ACM Transactions on Graphics 2025*

        **Fabricable Discretized Ruled Surface**
        A Bahrami, M Piovarci, M Tarini, B Bickel, N Pietroni — *Siggraph Asia 2025*

        **Rags2Riches: Computational Garment Reuse**
        A Qi, N Pietroni, M Korosteleva, O Sorkine-Hornung — *Siggraph 2025*

        **SkinMixer: Blending 3D Animated Models**
        S Nuvoli, N Pietroni, R Scateni, P Cignoni, M Tarini — *Siggraph Asia 2022*

        **Hex-Mesh Generation and Processing: a Survey**
        N Pietroni, M Campen, A Sheffer, G Cherchi, D Bommes et al. — *ACM TOG 2022*

        **Computational Pattern Making from 3D Garment Models**
        N Pietroni, C Dumery, R Guenot-Falque, M Liu, T Vidal-Calleja, O Sorkine-Hornung — *Siggraph 2022*

        **Volume Decomposition for Two-Piece Rigid Casting**
        T Alderighi, L Malomo, B Bickel, P Cignoni, N Pietroni — *Siggraph Asia 2021*

        **Reliable Feature-Line Driven Quad-Remeshing**
        N Pietroni, S Nuvoli, T Alderighi, P Cignoni, M Tarini — *Siggraph 2021*

        **LoopyCuts: Practical Feature-Preserving Block Decomposition**
        M Livesu*, N Pietroni*, E Puppo, A Sheffer, P Cignoni — *Siggraph 2020*

        **Reinforcement of General Shell Structures**
        FT Gil Ureta, N Pietroni, D Zorin — *ACM TOG 2020*

        **QuadMixer: Layout Preserving Blending of Quadrilateral Meshes**
        S Nuvoli, A Hernandez, C Esperanca, R Scateni, P Cignoni, N Pietroni — *Siggraph Asia 2019*

        **Volume-Aware Design of Composite Molds**
        T Alderighi, L Malomo, D Giorgi, B Bickel, P Cignoni, N Pietroni — *Siggraph 2019*

        **FlexMaps: Computational Design of Flat Flexible Shells for Shaping 3D Objects**
        L Malomo, J Pérez, E Iarussi, N Pietroni, E Miguel, P Cignoni, B Bickel — *Siggraph Asia 2018*

        **Metamolds: Computational Design of Silicone Molds**
        T Alderighi, L Malomo, D Giorgi, N Pietroni, B Bickel, P Cignoni — *Siggraph 2018*

        **Position Based Tensegrity Design**
        N Pietroni, M Tarini, A Vaxman, D Panozzo, P Cignoni — *Siggraph Asia 2017*

        **FlexMolds: Automatic Design of Flexible Shells for Molding**
        L Malomo, N Pietroni, B Bickel, P Cignoni — *Siggraph Asia 2016*

        **Data-Driven Interactive Quadrangulation**
        G Marcias, K Takayama, N Pietroni, D Panozzo, O Sorkine-Hornung, E Puppo, P Cignoni — *Siggraph 2015*

        **Elastic Textures for Additive Fabrication**
        J Panetta, Q Zhou, L Malomo, N Pietroni, P Cignoni, D Zorin — *Siggraph 2015*

        **Robust Field-Aligned Global Parametrization**
        A Myles, N Pietroni, D Zorin — *Siggraph 2014*

        **Field-Aligned Mesh Joinery**
        P Cignoni, N Pietroni, L Malomo, R Scopigno — *Siggraph Asia 2014*

        **Simple Quad Domains for Field Aligned Mesh Parametrization**
        M Tarini, E Puppo, D Panozzo, N Pietroni, P Cignoni — *Siggraph Asia 2011*

        **Global Parametrization of Range Image Sets**
        N Pietroni, M Tarini, O Sorkine, D Zorin — *Siggraph Asia 2011*

        **Feature-Aligned T-Meshes**
        A Myles, N Pietroni, D Kovacs, D Zorin — *Siggraph 2010*

        ---

        ### Other Journal Publications

        **Digital Garment Alteration** — *Computer Graphics Forum, Pacific Graphics 2024*
        **Bending the Light: Next Generation Anamorphic Sculptures** — *Computers & Graphics 2023*
        **HexBox: Interactive Box Modeling of Hexahedral Meshes** — *CGF SGP 2023*
        **State of the Art in Computational Mould Design** — *Computer Graphics Forum 2022*
        **Automatic Surface Segmentation for Seamless Fabrication** — *Eurographics 2021*
        **Automatic Design of Cable-Tensioned Glass Shells** — *Computer Graphics Forum 2020*
        **HexaLab.net: An Online Viewer for Hexahedral Meshes** — *Computer-Aided Design 2019*
        **State of the Art on Stylized Fabrication** — *Computer Graphics Forum 2018*
        **Tracing Field-Coherent Quad Layouts** — *Pacific Graphics 2016*
        **Statics Aware Grid Shells** — *Eurographics 2015*
        **Quad-Mesh Generation and Processing: A Survey** — *Computer Graphics Forum 2013*
        **Animation-Aware Quadrangulation** — *SGP 2013*
        **Almost Isometric Mesh Parameterization Through Abstract Domains** — *IEEE TVCG 2010*

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
