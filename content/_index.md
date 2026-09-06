---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: 'I am Assistant Professor of Mathematics at Dartmouth College. My research interests include Bayesian statistics, Monte Carlo methods, differential privacy, and applied statistics. Prior to Dartmouth, I completed my Ph.D. in Statistics at Harvard University and B.A. in Mathematics and Physics from Wellesley College.

      
      My Chinese name is 鞠念桥 and you can also call me Phyllis. You can contact me at `nianqiao DOT ju AT dartmouth DOT edu`.
      

      In my blog [phylliswithdata.wordpress.com](https://www.phylliswithdata.wordpress.com), I thrive to communicate statistical ideas and research in data privacy to a broad audience. I am on the organizing team of the [Online Monte Carlo Seminar](https://sites.google.com/view/monte-carlo-seminar). Follow us on [YouTube](https://www.youtube.com/@MonteCarloSeminar).


      If you are interested in working with me, you can apply for the [postdoc position](https://math.dartmouth.edu/activities/recruiting/recruiting_fliers_2026/PDSML-2026.pdf) on [mathjobs](https://www.mathjobs.org/jobs/list/26966) or to our [PhD program in math/applied math](https://math.dartmouth.edu/graduate-students/appl-info/).'
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
      headings:
        about: 'About me'
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true
      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: square # Options: circle (default), square, rounded
  - block: markdown
    id: news
    content:
      title: 'News'
      subtitle: ''
      text: |-
        - Honored to receive the 2025 [Blackwell-Rosenbluth Award](https://j-isba.github.io/blackwell-rosenbluth.html) by International Society for Bayesian Analysis. 
        - Fall 2025 season of [Online Monte Carlo Seminar](https://sites.google.com/view/monte-carlo-seminar) returns on September 23. 
        - I am joining the Department of Mathematics at Dartmouth College in July 2025. I am teaching MATH 20 (Probability) in Fall'25 and MATH 146 (Current topics in applied math, on data privacy and Bayesian statistics) in Winter'26.
        - New manuscript [SOMA: a novel sampler for exchangeable variables](https://arxiv.org/abs/2505.00635) with Yifei Xiong is on arxiv.
        - [Spectral gap bounds for reversible hybrid Gibbs chains](https://arxiv.org/abs/2312.12782) with Qian Qin and Guanyang Wang has been accepted by the *Annals of Statistics*. 
    design:
      columns: '1'
      css_style: 'width: 100%; max-width: 100%;'
  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: resume-awards
    id: awards
    content:
      title: Awards
      username: me
  - block: markdown
    id: grants
    content:
      title: 'Grants'
      text: |-
        - **NIH-NIAID**, *Systems biology to predict progression and treatment response in NTM pulmonary infections* (subaward from Mayo Clinic). July 2024 - June 2029.
        - **Showalter Trust Young Investigator Award**, Purdue University. July 2023 - June 2024.
        - **Biostatistics, Epidemiology, and Research Design (BERD) pilot program**, Indiana CTSI. May 2022 - April 2023.
    design:
      columns: '1'
      css_style: 'width: 100%; max-width: 100%;'
---
