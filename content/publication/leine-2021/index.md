---
title: 'Stability of Rigid Body Motion through an Extended Intermediate Axis Theorem:
  Application to Rockfall Simulation'
share: no
# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Remco I. Leine
- Giuseppe Capobianco
- Perry Bartelt
- Marc Christen
- Andrin Caviezel

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-08-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-03-28T11:02:12.787935Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

doi: 10.1007/s11044-021-09792-y

abstract: The stability properties of a freely rotating rigid body are governed by
  the intermediate axis theorem, i.e., rotation around the major and minor principal
  axes is stable whereas rotation around the intermediate axis is unstable. The stability
  of the principal axes is of importance for the prediction of rockfall. Current numerical
  schemes for 3D rockfall simulation, however, are not able to correctly represent
  these stability properties. In this paper an extended intermediate axis theorem
  is presented, which not only involves the angular momentum equations but also the
  orientation of the body, and we prove the theorem using Lyapunov’s direct method.
  Based on the stability proof, we present a novel scheme which respects the stability
  properties of a freely rotating body and which can be incorporated in numerical
  schemes for the simulation of rigid bodies with frictional unilateral constraints.
  In particular, we show how this scheme is incorporated in an existing 3D rockfall
  simulation code. Simulations results reveal that the stability properties of rotating
  rocks play an essential role in the run-out length and lateral spreading of rocks.

# Summary. An optional shortened abstract.
summary: ''

tags: [Rockfall, Natural Hazard Research]

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [real-world-applications]
# links:
# - name: URL
#   url: https://link.springer.com/10.1007/s11044-021-09792-y
---
