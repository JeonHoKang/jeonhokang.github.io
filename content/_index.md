---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    id: home
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /uploads/jeon-cv.pdf
    design:
      css_class: dark main
      background:
        color: black
        gradient_start: '#282B2C'
        gradient_end: '#2c3e50'
        # The gradient angle from 0-360 degrees
        gradient_angle: 30
        # text:
        #   size: 4em


  - block: markdown
    id: news
    weight: 25
    content: 
      text: |-
        ## News
        - **September 2026**: Our paper titled **[Vision-Language Grounded Task-Context-Aware Imitation Learning for Robotic Disassembly](https://arxiv.org/abs/2609.17714)** has been accepted to **IEEE Robotics and Automation Letters (RA-L)**!
        - **May 2026**: Joined **Amazon** as an **Applied Scientist II Intern**!
        - **April 2025**: Now our paper, code and dataset can be accessed via [Arxiv](https://arxiv.org/abs/2503.03998), [Papers with code](https://cs.paperswithcode.com/paper/robotic-compliant-object-prying-using), and [Hugging Face](https://huggingface.co/datasets/Jeon-hk/Battery_Prying_Dataset/blob/main/README.md) !
        - **March 2025**: Looking forward to interning at **Honda Resarch Institute** this summer as Resesarch Scientist Intern working on **Behavior Models for Dexterous Manipulation**!
        - **March 2025**: Our paper on Compliant Object prying has been accepted on Robotics and Automation Letters!
        - **March 2024**: Our paper at MSEC 2024 won the **Best Conference Paper Award**!
        - **February 2024**: Our paper on **Lage Language Moddels for Contingency Recovery and Task Allocation** has been accepted for publication at **ICRA 2024**!

    design:
      columns: '2'
      css_style: 'font-size: 2.0rem; text-align: left; width: 100%; max-width: none'
      css_class: custom-bullets
      background:
        color: light
        gradient_start: '#282B2C'
        gradient_end: '#2c3e50'
        # The gradient angle from 0-360 degrees
        gradient_angle: 60
      
  - block: collection
    id: research
    content:
      title: Research
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
      css_class: dark
      background:
        gradient_start: '#282B2C'
        gradient_end: '#2c3e50'
        # The gradient angle from 0-360 degrees
        gradient_angle: 30

  
  - block: resume-experience 
    id: experience
    content: 
      # title: Experience
      username: admin
      hide_education: true

    design:
      css_class:  custom-position dark

      background:
        color: black
        gradient_start: '#282B2C'
        gradient_end: '#2c3e50'
        # The gradient angle from 0-360 degrees
        gradient_angle: 30
      date_format z: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
      
      
  - block: collection
    id: publications
    content:
      title: Publications
      text: ""
      count: 10
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      css_class: dark citation-dark
      background:
        color: black
        gradient_start: '#282B2C'
        gradient_end: '#2c3e50'
        # The gradient angle from 0-360 degrees
        gradient_angle: 30

  
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
        
    design:
      view: article-grid
      columns: 3
      css_class: dark
      background:
        color: black
        gradient_start: '#282B2C'
        gradient_end: '#2c3e50'
        # The gradient angle from 0-360 degrees
        gradient_angle: 30


  - block: resume-skills 
    id: skills
    content: 
      title: Skills & courses
      # title: Experience
      username: admin

    design:
      css_class:  custom-position dark
      columns: 2
      background:
        color: black
        gradient_start: '#282B2C'
        gradient_end: '#2c3e50'
        # The gradient angle from 0-360 degrees
        gradient_angle: 30
      date_format z: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  

  # - block: resume-languages
  #   content:
  #     title: Languages
  #     username: admin

  
  - block: resume-awards
    id: awards
    content:
      title: Accomplishments
      username: admin
    design:
      css_class: dark
      background:
        color: black
        gradient_start: '#282B2C'
        gradient_end: '#2c3e50'
        # The gradient angle from 0-360 degrees
        gradient_angle: 30
        text:
          size: 1.5em


---