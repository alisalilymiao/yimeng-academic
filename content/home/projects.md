---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: Experience

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
    location: Melbourne
    date_start: '2020-04-01'
    date_end: '2020-07-20'
    description: |2-
        Responsibilities include:
        
        * Participated in the development of a Web page game based on user action recognition. The match between the user action and the target action determines the score of the game
        * Back-end technologies used the TFJS-Models/PoseNet open-source image recognition algorithm to identify user action according to the coordinates of the two-dimensional image

  - title: Voice Meeting Application
    company: The University of Melbourne
    company_url: ''
    company_logo: 
    location: Melbourne
    date_start: '2019-09-20'
    date_end: '2019-12-20'
    description: |2-
        Responsibilities include:
        
        * Used the MFCC feature extraction method to transfer the frequency band from the HZ scale to the Mel scale. Trained a hybrid  GMM model using non-target user voice data and fine-tune it based on the data of the target user
        * Utilized the distance-based segmentation algorithm for speaker segmentation. Pattern matching and logical decision-making used maximum Posterior Probability Classification


  - title: Peer-to-Peer File Transformation Project
    company: The University of Melbourne
    company_url: ''
    company_logo: 
    location: Melbourne
    date_start: '2019-03-20'
    date_end: '2019-07-20'
    description: |2-
        Responsibilities include:
        
        * Used the TCP socket interface provided by Java to connect each peer and used a multithread mechanism to implement synchronized peer-to-peer communication for file transmission
        * Implemented security mechanisms through asymmetric and symmetric encryption algorithms

design:
  columns: '2'
---
