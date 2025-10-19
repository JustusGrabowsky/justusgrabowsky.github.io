---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  # Profile / About card
  - block: resume-biography-3
    content:
      username: admin
      text: |-
        I am a PhD student at the Institute of Neuroinformatics (ETH Zürich & UZH) working on the neural dynamics of speech under the supervision of Timothée Proix. Previously, I was a visiting researcher at Yale University, where I worked on computational materials science with Diana Qiu. I hold a Bachelor’s and a Master’s degree in Physics from ETH Zürich.

        **Education:**
        - *Visiting Assistant in Research*, **Yale University**, New Haven (Oct 2024 – May 2025)  
          *Master’s Thesis: GW-BSE Study of the Band Structure and Optical Spectrum of Layered CrSBr*  
          Supervisors: Prof. Diana Qiu (Yale) & Prof. Juan Carrasquilla (ETH Zürich)
        - *Physics MSc*, **ETH Zürich**, Switzerland (Sep 2023 – present)  
          Semester project: *Machine-Learned Interatomic Potential for BaTiO₃*  
          Supervisors: Prof. Nicola Spaldin & Prof. Mathieu Luisier
        - *Exchange Student*, **École Normale Supérieure (ENS Paris)**, France (Sep 2022 – Jun 2023)
        - *Physics BSc*, **ETH Zürich**, Switzerland (Sep 2020 – Sep 2023)  
          Bachelor’s project: *Ultra-Strong Light-Matter Coupling in THz LC Resonators*  
          Supervisor: Prof. Carlo Sirtori (ENS Paris)

        **Interests:** neural dynamics, neuroscience, AI for science
      button:
        text: Download CV
        url: /cv.pdf
      headings:{}
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  # Research (projects) grid
  - block: collection
    content:
      title: Research
      text: ''
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2

  # Publications (citation list)
#  - block: collection
#    id: publications
#    content:
#      title: Publications
#      text: ''
#      filters:
#        folders:
#          - publications
#    design:
#      view: citation

  # Contact section
  - block: markdown
    content:
      title: Contact
      subtitle: ''
      text: |-
        You can reach me by email: <a href="mailto:jgrabowsky@ethz.ch">jgrabowsky@ethz.ch</a>
    design:
      columns: '1'
---
