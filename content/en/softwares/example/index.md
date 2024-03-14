---
title: InVesalius Navigator

event: Wowchemy Conference
event_url: https://example.org

location: Wowchemy HQ
address:
  street: 450 Serra Mall
  city: Stanford
  region: CA
  postcode: '94305'
  country: United States

summary: Software for neuronavigation, visualization and manipulation of medical images.
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


The InVesalius Navigator is a free software for visualization and manipulation of medical images, and virtual navigation. It has been under development since October 2008 by the Biomagnetism Laboratory of the Faculty of Philosophy, Sciences and Letters of Ribeirão Preto at the University of Sao Paulo, in partnership with the Renato Archer Information Technology Center of the Ministry of Science and Technology. The initial motivation for its creation came from the difficulty faced by research centers and hospitals in acquiring virtual navigation systems, due to the high cost and importation difficulties.

The functionalities involve the manipulation and editing of medical images from Nuclear Magnetic Resonance tomographs, Computed Tomography and 3D Scanners. Virtual navigation is performed using spatial tracking equipment, making it possible to identify the real-time positioning of a pointer in relation to target structures, represented in the viewing windows, facilitating, for example, the planning of neurosurgeries.

Currently, the InVesalius Navigator is being used in transcranial magnetic stimulation (TMS) procedures, for the positioning of the stimulation coil over the cortex to be stimulated, and to quantify the relative orientation of the instrument to the reference planes of the subject's head. The software is also used to acquire the spatial coordinates of the stimulated points in a motor mapping experiment with TMS.

The virtual navigator is developed in Python language, and uses the graphic library wxPython, the numerical library Numpy and the Visualization Toolkit (VTK) library for visualization. All of these tools are free. The source code is open and free, with an interface available in eight languages, compatibility with Windows, Linux and Mac OS, both 32 and 64 bits, and communication with five different models of spatial trackers from Polhemus (Polhemus - Colchester, United States), Claron (Claron Technology Inc. - Toronto, Canada) and Zebris (zebris Medical GmbH - Isny im Allgäu, Germany), are its main advantages compared to similar ones in the market. In terms of accuracy, the InVesalius Navigator is comparable to its competitors, but in terms of compatibility it has an extreme advantage.

For more information on downloading InVesalius, please visit the CTI website or contact us through our Contact page.
