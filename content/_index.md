---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-01-05
type: landing

sections:
  # Developer Hero - Gradient background with name, role, social, and CTAs
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: "Hi, I'm"
      show_status: true
      show_scroll_indicator: true
      typewriter:
        enable: true
        prefix: "I build"
        strings:
          - "Indie games"
          - "scalable Apps"
          - "open source tools"
        type_speed: 70
        delete_speed: 40
        pause_time: 2500
      cta_buttons:
        - text: View My Work
          url: "#projects"
          icon: arrow-down
        - text: Get In Touch
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: circle
      animations: true
      background:
        color:
          light: "#fafafa"
          dark: "#0a0a0f"
      spacing:
        padding: ["6rem", "0", "4rem", "0"]
  
  # Filterable Portfolio - Alpine.js powered project filtering
  - block: portfolio
    id: projects
    content:
      title: "Featured Projects"
      subtitle: "A selection of my recent work"
      count: 0
      filters:
        folders:
          - projects
      buttons:
        - name: All
          tag: '*'
        - name: Game Dev
          tag: Game-Dev
        - name: Programming
          tag: Programming
      default_button_index: 0
      # Archive link auto-shown if more projects exist than 'count' above
      # archive:
      #   enable: false  # Set to false to explicitly hide
      #   text: "Browse All"  # Customize text
      #   link: "/work/"  # Custom URL
    design:
      columns: 3
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # Visual Tech Stack - Icons organized by category
  - block: tech-stack
    id: skills
    content:
      title: "Tech Stack"
      subtitle: "Technologies I use to build things"
      categories:
        - name: Languages
          items:
            - name: Python
              icon: devicon/python
            - name: C#
              icon: devicon/charp
            - name: C/C++
              icon: devicon/cplusplus
            - name: Java
              icon: devicon/java
        - name: DevOps
          items:
            - name: GitHub Actions
              icon: brands/github
            - name: CI/CD
              icon: brands/jenkins
        - name: Game Development
          items:
            - name: Unity Engine
              icon: devicon/Unity
        - name: Database
          items:
            -name: MySQL
             icon: devicon/mysql
    design:
      style: grid
      show_levels: false
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # Experience Timeline
  - block: resume-experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2006
      items:
        - title: Software Engineer
          company: Fev Romania
          company_url: ''
          company_logo: ''
          location: Bucharest, Romania
          date_start: '2022-07-08'
          date_end: ''
          description: |2-
            * Model-Based Development
            * C/C++ Core Programming
            * Python Application Development
            * CI/CD Automation
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # Contact Section
  - block: contact-info
    id: contact
    content:
      title: Get In Touch
      subtitle: "Let's build something amazing together"
      text: |-
        I'm always interested in hearing about new projects and opportunities.
        Whether you're looking to hire, collaborate, or just want to say hi, feel free to reach out!
      email: mariusvalentin9918@gmail.com
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#ffffff"
          dark: "#0d0d12"
      spacing:
        padding: ["4rem", "0", "4rem", "0"]
  
  # CTA Card
  - block: cta-card
    content:
      title: "Open to Opportunities"
      text: |-
        I'm currently looking for **game development** or **software engineering** roles.
        
        Let's connect and discuss how I can help your team.
      button:
        text: 'Download Resume'
        url: uploads/resume.pdf
        new_tab: true
    design:
      card:
        # Light mode: soft pastel theme gradient | Dark mode: rich deep gradient
        css_class: 'bg-gradient-to-br from-primary-200 via-primary-100 to-secondary-200 dark:from-primary-600 dark:via-primary-700 dark:to-secondary-700'
        text_color: dark
      background:
        color:
          light: "#f5f5f5"
          dark: "#08080c"
      spacing:
        padding: ["4rem", "0", "6rem", "0"]
---
