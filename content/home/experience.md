---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
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
  - title: Software Engineer
    company: Meituan 
    company_url: 'https://i.meituan.com/'
    company_logo: org-meituan
    location: Beijing, China
    date_start: '2020-01'
    date_end: ''
    description: |2-
        Responsibilities include:
        
        *  Participated in the reconstruction of the payment contract software system and assisted in building the platform services of core capabilities - signing, cancellation, and authentication, which allowed future expansion
        * Used design patterns such as factory pattern, strategy pattern, SPI design, and chain of responsibility design pattern to abstract system public process, settled reusable modules, and regularized interface definition
        * Extracted key business indicators for monitoring and tracking the fluctuation of the system. Configured alarms to ensure that the reconstruction quality risk is minimized
        *  Built an intelligent operation system, matched the information in the resource database according to the keywords entered by users, and used the front-end page to display the retrieval results

  - title: Android Developer and Web developer(Intern) 
    company: INHAABIT 
    company_url: 'https://inhaabit.com/'
    company_logo: org-inhaabit
    location: Melbourne, Australia
    date_start: '2019-11'
    date_end: '2020-03'
    description: |2-
        Responsibilities include:
       
        *  Assisted with the interface development of an Android app for Augmented Reality (AR), project wireframing, CMS content management tasks, and HTML and CSS form building
        * Wrote and performed unit tests and interface tests to ensure the correctness of system functions. Collaborated with other developers to identify and alleviate several bugs and errors in software

  - title: Software Developer(Intern)
    company: Neusoft 
    company_url: 'https://www.neusoft.com/'
    company_logo: org-neusoft
    location: Shenyang, China
    date_start: '2018-11'
    date_end: '2019-03'
    description: |2-
        Responsibilities include:
       
        *  Responsible for data model refactoring to ensure the correctness and stability of the data. The data reconstruction strategy is to block the increment and wash the stock
        * Double wrote the incremental data into the new model, and use the monitoring tool to check the correctness of the data stream
        * Controlled data cleaning procedure by adding cleaning switch, breakpoint record, and RateLimter to the data cleaning system. If there is an anomaly in the cleaning process, connect the corresponding notification tool to ensure that the cleaning process can be sensed

design:
  columns: '2'
---
