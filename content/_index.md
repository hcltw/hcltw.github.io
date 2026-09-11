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
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV · Updated Sep 9, 2026
        url: uploads/resume.pdf
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
      title: '[MILD Lab](/lab/) is Recruiting'
      subtitle: ''
      text: |-
        - **Position:** Master's Students
        - **Research Topics:** Recommender Systems, Social Networks, Intelligent Decision-Making, or other Data Mining and Machine Learning topics you are passionate about
        - **Preferred Skills:** Python, basic machine learning, independent learning

        To apply, email me with your CV, transcript, and a brief, relevant research proposal.
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
