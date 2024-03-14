---
title: Mep Hunter

event: Wowchemy Conference
event_url: https://example.org

location: Wowchemy HQ
address:
  street: 450 Serra Mall
  city: Stanford
  region: CA
  postcode: '94305'
  country: United States

summary: Software for analysis and visualization of electrophysiological.
abstract: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellusac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2030-06-01T13:00:00Z'
date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---


Analysis and visualization of electrophysiological data is a stage that demands a lot of work and time in an experimental procedure. Additionally, many researchers spend a lot of time learning computer programming to write scripts and analyze their own data. This common habit occurs because many available programs are expensive or difficult to use. Many of them do not have a graphical interface for the user and have a limited number of functionalities. Driven by this, we developed MEPHunter, a free software to facilitate the analysis and processing of electrophysiological data.

MEPHunter (Motor Evoked Potentials Hunter) started to be developed in 2011, with the initial goal being the quick and easy analysis of surface electromyography (EMG) data recorded in a transcranial magnetic stimulation (TMS) experiment. It is written in MATLAB v7.8 (MathWorks, Natick, USA) and is fully compatible with subsequent versions. In the following years, with many collaborators, suggestions, and experience gained in the experimental field, we felt the need to expand MEPHunter to other applications.

The aim of MEPHunter is to be software that allows the analysis of data and visualization of electrophysiological signals with a user-friendly graphical interface. MEPHunter provides a set of functions to separate continuous data into temporal graphs. It also has functions for bandpass filtering, amplitude calculations, and map creation. Users can interact directly with the automatic markers created by the software and change them according to their needs. The software can read data exported by four different models of sEMG amplifiers and can export processing results to a text file or an Excel file for future statistical analysis. MEPHunter was developed following object-oriented programming rules. Adding new functionalities and interfaces can be done by creating new plug-ins, enabling the continuous development of the software.

The development of MEPHunter as free software allows users from research centers and academic environments to use it for research and teaching purposes.
