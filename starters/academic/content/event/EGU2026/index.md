---
title: Talk at EGU 2026 Session BG3.5

event: EGU General Assembly 2026
event_url: "https://www.egu26.eu/"
#date_format: 'yyyy-mm-ddThh:mm:ssZ'

location: Vienna, Austria

summary: EEO theory for photosynthesis and respiration in gridded standalone JULES for simulating better carbon fluxes
abstract: 'Land surface models (LSMs) often exhibit substantial biases in simulating vegetation photosynthesis and respiration, largely due to their reliance on numerous plant functional type (PFT)–specific parameters. Recent advances based on Eco-Evolutionary Optimality (EEO) theory suggest that many of these parameters can be reduced, as vegetation carbon fluxes can be represented using universal optimal light and carboxylation conditions rather than prescribed PFT-dependent traits. Studies have demonstrated that EEO-based approaches perform remarkably well across a wide range of FLUXNET sites. In this study, we implement an EEO-based photosynthesis scheme within the gridded Joint UK Land Environment Simulator (JULES) to evaluate the scalability and performance of the theory at the global scale. This is a critical step beyond site-level evaluation of the theory, enabling assessment of EEO under diverse climatic and ecological conditions worldwide. We compare simulations from the EEO-enabled JULES configuration (JULES-EEO) against two model variants: JULES-NoAdap_NoAcclim, and JULES-Acclim; both of which rely on PFT-specific parameterizations. JULES-NoAdap_NoAcclim assumes no vegetation adaptation or acclimation, while JULES-Acclimation incorporates thermal acclimation following the Kumarathunge scheme. Through this intercomparison, we assess whether EEO can robustly reduce biases in global carbon flux simulations relative to conventional pft-parameter formulations. Superior performance of the EEO-based model offers the potential for improved computational efficiency by eliminating iterative, PFT-specific calculations, thereby enhancing overall model speed. The results provide new insights into the applicability of eco-evolutionary optimality theory at global scales and help identify potential pathways for further refinement of vegetation process representations in Earth system models.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-05-05T10:55:00Z'
date_end: '2026-05-05T11:05:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2026-09-09T21:05:00Z'

authors: [Narender Kangari, Wenyao Gan, Pier Luigi Vidale, Martin Best]
tags: []

# Is this a featured talk? (true/false)
featured: true

image:
  #caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  - icon: doi
    icon_pack: fab
    name: abstract
    url: https://doi.org/10.5194/egusphere-egu26-12215
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

projects:
  - CONCERTO
---
