---
title: Development of event-capturing schemes for mechanical systems with frictional contact
summary: The mechanics of systems involving frictional contact can be effectively described within the framework of nonsmooth mechanics. This theoretical approach permits the velocities of the system to experience sudden jumps due to impacts. The objective of this research is to create specialized numerical algorithms capable of efficiently handling the nonsmooth behavior that is intrinsic to the simulation and optimal control of such systems.

tags:
  - Nonsmooth Dynamics
  - Numerical Methods
date: '2024-03-26T00:00:00Z'

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

It is well known that the dynamics of multibody systems with frictional contact is nonsmooth, i.e., these systems can for example exhibit velocity jumps due to impacts whenever a unilateral constraint becomes active. For the numerical simulation of nonsmooth mechanical systems, two classes of schemes can be distinguished, namely the event-driven and the event-capturing schemes. The distinguishing property of event-driven schemes is that they accurately resolve every discontinuity point, i.e., every time instant at which for example a slip-stick transition or an impact occurs is precisely determined. In contrast, the event-capturing schemes approximate all discontinuities occurring within a time step qualitatively. Accurately resolving every single discontinuity point is computationally very expensive, especially if the system’s dynamics exhibits a large number of discontinuities. This is typically the case for engineering systems, since they have many possible contact points. There are even cases where the dynamics shows an accumulation point, i.e., an infinite number of discontinuities occurring in a finite interval of time. It is immediately clear that an event-driven scheme will not be able to overcome such an accumulation point. It is the major advantage of event-capturing schemes that they can overcome accumulation points and that they can efficiently simulate motions with many discontinuities. 