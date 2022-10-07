---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Research Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: User Action Detective Application
    company: Codejoy
    company_url: ''
    company_logo: 
    location: Beijing
    date_start: '2020-03-24'
    date_end: '2020-07-20'
    description: |2-
        Responsibilities include:
        
        * Participated in the development of a Web page game based on user action recognition. The match between the user action and the target action determines the score of the game
        * Back-end technologies used the TFJS-Models/PoseNet open-source image recognition algorithm to identify user action according to the coordinates of the two-dimensional image

  - title: Android Developer and Web developer
    company: INHAABIT 
    company_url: 'https://inhaabit.com/'
    company_logo: 
    location: Melbourne
    date_start: '2019-09-01'
    date_end: '2019-12-20'
    description: |2-
        Responsibilities include:
        
        * Assisted with the interface development of an Android app for Augmented Reality (AR), project wireframing, CMS content management tasks, and HTML and CSS form building
        * Wrote and performed unit tests and interface tests to ensure the correctness of system functions. Collaborated with other developers to identify and alleviate several bugs and errors in software

  - title: Software Developer
    company: Neusoft 
    company_url: 'https://inhaabit.com/'
    company_logo: 
    location: Shenyang
    date_start: '2018-11-01'
    date_end: '2019-03-20'
    description: |2-
        Responsibilities include:
        
        * Responsible for data model refactoring to ensure the correctness and stability of the data. The data reconstruction strategy is to block the increment and wash the stock
        * Double wrote the incremental data into the new model, and use the monitoring tool to check the correctness of the data stream
        * Controlled data cleaning procedure by adding cleaning switch, breakpoint record, and RateLimter to the data cleaning system. If there is an anomaly in the cleaning process, connect the corresponding notification tool to ensure that the cleaning process can be sensed

design:
  columns: '2'
---
