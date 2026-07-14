---
draft: false
title: Soft Pneumatic Actuator
summary: To describe the mechanical behavior of a soft pneumatic actuator, we present a nonlinear rod theory, which recognizes the chamber pressurization as contribution to the resultant contact forces and couples. Accordingly, the pressure actuation can be considered as part of the rod’s constitutive laws, which relate the contact interactions with the rod’s kinematics and the chamber pressures. The theory allows for nonlinear constitutive laws, which are capable of describing strengthening or softening behavior of largely deformable materials. The theory was applied to a three-chamber actuator to predict its centerline as well as the cross-section orientations in static equilibrium.

tags:
  - Real-world problems
  - Engineering applications
  - Soft Pneumatic Actuator
  - Numerical Methods
date: '2024-03-20T00:00:00Z'

# deactivate share-box at the end of project
share: no

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: © G. Capobianco
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---
To describe the mechanical behavior of a soft pneumatic actuator, we present a nonlinear rod theory, which recognizes the chamber pressurization as contribution to the resultant contact forces and couples. Accordingly, the pressure actuation can be considered as part of the rod’s constitutive laws, which relate the contact interactions with the rod’s kinematics and the chamber pressures. The theory allows for nonlinear constitutive laws, which are capable of describing strengthening or softening behavior of largely deformable materials. The theory was applied to a three-chamber actuator to predict its centerline as well as the cross-section orientations in static equilibrium. The resulting governing equations were spatially discretized using beam finite elements. We evaluated four different actuator models that are contained in the presented theory regarding describability and predictability of the end effector position. Existing rod models with linear elastic material laws can describe the tip-displacement with an averaged deviation of 9.1 mm in the training set and 11.4 mm in the test set. With a deviation of 2.8 mm and 4.9 mm in the training and test set, respectively, the most enhanced model, for which the pressure chamber radii increase with increasing pressure, is more than two times more accurate.