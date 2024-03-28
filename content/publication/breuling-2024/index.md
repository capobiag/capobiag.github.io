---
title: A Nonsmooth RATTLE Algorithm for Mechanical Systems with Frictional Unilateral
  Constraints

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Jonas Breuling
- Giuseppe Capobianco
- Simon R. Eugster
- Remco I. Leine

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-05-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-03-28T11:02:12.704703Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: ''
publication_short: ''

doi: 10.1016/j.nahs.2024.101469

abstract: In 1983, Andersen proposed the RATTLE algorithm as an extension of the SHAKE
  algorithm. The RATTLE algorithm is a well-established method for simulating mechanical
  systems with perfect bilateral constraints. This paper further extends RATTLE for
  simulating nonsmooth mechanical systems with frictional unilateral constraints (i.e.
  frictional contact). With that, it satisfies the need for higher-order integration
  methods within the framework of nonsmooth contact dynamics in phases where the contact
  status does not change (i.e. no collisions/constant sliding states). In particular,
  the proposed method can simulate impact-free motions, such as persistent frictional
  contact, with second-order accurate positions and velocities and prohibits penetration
  by unilateral constraints on position level.

# Summary. An optional shortened abstract.
summary: ''

tags: [Nonsmooth Dynamics, Numerical Methods]

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
projects: [event-capturing-sim]
# links:
# - name: URL
#   url: https://linkinghub.elsevier.com/retrieve/pii/S1751570X24000062

# deactivate share-box at the end of project
share: no

---
