---
title: Researcher Personal Site Homepage
summary: "Homepage with bio, publications, projects, talks, teaching, and CV sections."
date: 2026-07-21
type: landing
sections:
  - block: hero
    content:
        eyebrow: Welcome
        title: Dr. Felix Meickmann
        text: "I am a dedicated researcher specialising in computational linguistics, AI, and data science. Explore my publications, projects, talks, teaching, and CV via the sections below."
        primary_action:
          text: View Publications
          url: "#publications"
          icon: hero/book-open
        secondary_action:
          text: About Me
          url: "#bio"
          icon: hero/user
    design:
        background:
          gradient:
            type: radial
            start: primary-500
            end: transparent
            position: center
            shape: ellipse
            size: "80% 80%"
        text_color_light: true
    id: welcome
  - block: collection
    content:
        title: About Me
        text: Brief biography and research interests.
        count: 1
        page_type: page
        sort_by: Date
        filters:
          folders:
            - bio
    design:
        background:
          color:
            light: primary-50
            dark: primary-900
    id: bio
  - block: collection
    content:
        title: Publications
        text: Latest research publications and journals.
        count: 8
        page_type: publication
        sort_by: Date
    design:
        background:
          color:
            light: secondary-50
            dark: secondary-900
    id: publications
  - block: collection
    content:
        title: Projects
        text: Research and development projects.
        count: 5
        page_type: project
        sort_by: Date
    design:
        background:
          color:
            light: accent-50
            dark: accent-900
    id: projects
  - block: collection
    content:
        title: Talks
        text: "Conferences, seminars, and invited talks."
        count: 5
        page_type: event
        filters:
          folders:
            - talk
            - event
        sort_by: Date
    design:
        background:
          color:
            light: info-50
            dark: info-900
    id: talks
  - block: collection
    content:
        title: Teaching
        text: Courses and lectures.
        count: 5
        page_type: page
        filters:
          folders:
            - teaching
        sort_by: Date
    design:
        background:
          color:
            light: success-50
            dark: success-900
    id: teaching
  - block: collection
    content:
        title: Curriculum Vitae
        text: Academic and professional history.
        count: 1
        page_type: page
        filters:
          folders:
            - cv
    design:
        background:
          color:
            light: warning-50
            dark: warning-900
    id: cv
---
