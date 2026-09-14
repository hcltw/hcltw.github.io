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
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      css_class: dark
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'CGU LaMI Lab is Recruiting'
      subtitle: ''
      text: |-
        CGU LaMI welcomes passionate and creative M.S. students who enjoy exchanging ideas and working through research questions together. Please see the [Lab page](/lab/) for our research directions and complete application details.
    design:
      columns: '1'
      css_class: recruiting-students-section
  - block: career-timelines
    content:
      username: admin
      experience_title: Experience
      talks_title: Invited Talks & Outreach
      talks:
        - title: What Is Machine Learning? Build Your Own Game Controller with AI
          venue: Tatung High School
          date: 2026-07-01
          type: Outreach
        - title: 'Recommender Systems: From Social Apps to Healthcare'
          venue: Kanazawa University
          date: 2026-06-01
          type: Seminar
        - title: 'Recommender Systems: From Social Apps to Healthcare'
          venue: Department of Information Management, National Taiwan University of Science and Technology
          date: 2026-05-01
          type: Seminar
        - title: 'Recommender Systems: From Social Apps to Healthcare'
          venue: Computer Science Seminar, National Yang Ming Chiao Tung University
          date: 2026-03-01
          type: Seminar
    design:
      spacing:
        padding: ['4rem', '0', '5rem', '0']
---
