---
title: Amrita SAIL Lab
design:
  spacing: 6rem
type: landing
sections:
  - block: hero
    content:
        eyebrow: Applied Research & Innovation Lab
        title: "Developing [Language Intelligence] for Social Good"
        text: We apply AI and NLP to real-world societal challenges, with a focus on low-resource and multilingual settings and Indian languages.
        primary_action:
          text: Explore Our Research
          url: "#our-research"
          icon: hero/magnifying-glass
          style: gradient
        secondary_action:
          text: Meet the Team
          url: "#team-collaborators"
          icon: hero/users
          style: ghost
    design:
        background:
          color:
            light: "#ffffff"
            dark: "#ffffff"
          gradient:
            type: linear
            start: red-600
            end: red-400
            direction: 90
        text_color_light: false
        spacing:
          padding: [6rem, 0, 6rem, 0]
  - block: features
    content:
        title: Our Research Focus
        text: "Societal Problem → Language Data → Research → Intelligent Systems → Applications → Deployment → Impact"
        items:
          - name: Research
            description: New methods, datasets, models, and evaluation approaches in NLP, AI, and language intelligence.
            icon: hero/academic-cap
          - name: Build
            description: Turning research into prototypes, platforms, tools, and applications for real-world problems.
            icon: hero/wrench-screwdriver
          - name: Impact
            description: Working with communities and institutions to evaluate and deploy technology for social value.
            icon: hero/heart
          - name: Multilingual & Low-Resource NLP
            description: Online safety, health information, climate, civic engagement, education, and language accessibility.
            icon: hero/language
    design:
        background:
          color: white
        layout: grid
    id: our-research
  - block: team-showcase
    content:
        title: "Team & Collaborators"
        subtitle: Meet our researchers and partners
        text: Department of Computer Science & Engineering, School of Computing, Amrita Vishwa Vidyapeetham, Amritapuri Campus.
        user_groups:
          - Principal Investigators
          - Research Engineers
          - PhD Students
          - Alumni
        sort_by: name_family
        sort_ascending: true
        cta:
          text: Join Our Team
          url: /careers
          icon: hero/user-plus
    design:
        background:
          color: "#ffeaea"
        show_role: true
        show_organizations: true
        show_interests: false
        show_social: true
        max_interests: 3
        align: center
        max_columns: 4
    id: team-collaborators
  - block: gallery
    content:
        title: Our Projects
        subtitle: Language technologies with real-world impact
        items:
          - src: media/projects/project1.jpg
            title: Project 1
            caption: Replace with a SAIL project.
            alt: Project 1 screenshot
          - src: media/projects/project2.jpg
            title: Project 2
            caption: Replace with a SAIL project.
            alt: Project 2 screenshot
          - src: media/projects/project3.jpg
            title: Project 3
            caption: Replace with a SAIL project.
            alt: Project 3 screenshot
    design:
        layout: grid
        columns: 3
        gap: md
        caption_position: below
    id: projects
  - block: collection
    content:
        title: Publications
        subtitle: Recent papers and articles
        text: Browse our latest research outputs and scholarly articles.
        types:
          - publication
        sort_by: date
        sort_ascending: false
    design:
        background:
          color: white
    id: publications
  - block: contact-info
    content:
        title: Get in Touch
        text: "We welcome inquiries, collaborations, and opportunities to advance language intelligence for social good."
        email: "anoopvs@am.amrita.edu"
        address: "Dept. of CSE, School of Computing, Amrita Vishwa Vidyapeetham, Amritapuri Campus, Kollam, India - 690525"
    design:
        background:
          color: "#ffeaea"
    id: contact
---
