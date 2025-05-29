---
title: 'BAND: Behavior-Aligned Neural Dynamics is all you need to capture motor corrections'
authors:
- Nina Kudryashova
- Cole Hurwitz
- Matthew G Perich
- Matthias H Hennig
date: '2025-01-01'
publishDate: '2025-05-29T09:36:20.309868Z'
publication_types:
- article-journal
publication: '*bioRxiv*'

abstract: Neural activity in motor cortical areas is well-explained by latent neural population dynamics: the motor preparation phase sets the initial condition for the movement while the dynamics that unfold during the motor execution phase orchestrate the sequence of muscle activations. While preparatory activity explains a large fraction of both neural and behavior variability during the execution of a planned movement, it cannot account for corrections and adjustments during movements as this requires sensory feedback not available during planning. Therefore, accounting for unplanned, sensoryguided movement requires knowledge of relevant inputs to the motor cortex from other brain areas. Here, we provide evidence that these inputs cause transient deviations from an autonomous neural population trajectory, and show that these dynamics cannot be found by unsupervised inference methods. We introduce the new Behavior-Aligned Neural Dynamics (BAND) model, which exploits semi-supervised learning to predict both planned and unplanned movements from neural activity in the motor cortex that can be missed by unsupervised inference methods. Our analysis using BAND suggests that 1) transient motor corrections are encoded in small neural variability; 2) motor corrections are encoded in a sparse sub-population of primary motor cortex neurons (M1); and 3) combining latent dynamical modeling with behavior supervision allows for capturing both the movement plan and corrections.

# Summary. An optional shortened abstract.
summary: Motor cortical neural activity is commonly viewed as a low-dimensional dynamics evolving from the movement preparation state, which explains the most of both neural and behavioral variability. We found that movement corrections to unexpected behavior perturbations do not follow the same pattern, with only a small fraction of neural variability explaining large changes in behavior. We show that capturing both movement planning and corrections requires models that incorporate dynamics and weak behavior supervision. We characterize the bidirectional relationships between motor cortical activity and behavior, identifying neural code for both feedforward and feedback-driven motor control

tags:
  - Latent neural population dynamics
  - Motor control

# Display this page in the Featured widget?
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'BAND summary'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}
