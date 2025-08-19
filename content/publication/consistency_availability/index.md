---
title: 'Edge AI in the computing continuum: Consistency and Availability at Early Design Stages'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Claudio Savaglio
  - Edward A. Lee
  - Giancarlo Fortino

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-06-03T00:00:00Z'
doi: 'https://doi.org/10.1109/IPDPSW66978.2025.00175'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-06-03T00:00:00Z'

# Publication type.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: 2025 IEEE International Parallel and Distributed Processing Symposium Workshops (IPDPSW)
publication_short: ""

abstract: >
  This paper explores the integration of Edge Intelligence (EI) with the coordination language LINGUA FRANCA (LF), leveraging the Consistency-Availability-Latency (CAL) theorem as the theoretical foundation to optimize Cyber-Physical Systems (CPS) design and deployment. We propose a distributed EI-based approach for CPS to develop an Emergency Vehicle Detection (EVD) system that dynamically adjusts traffic signals at intersections to prioritize emergency vehicles, improving emergency response times while maintaining traffic efficiency. The system employs multimodal detection techniques, including audio classification and object detection, and utilizes LF’s deterministic coordination to ensure seamless execution across the computing continuum. We analyze two deployment scenarios: cloud-assisted and fully edge-based. The CAL theorem guides tradeoffs between consistency, availability, and latency, informing optimal service placement at design time. Experimental results validate the theoretical analysis, showing that the edge-based deployment achieves 2.8x lower inference-to-actuation latency and 10.26% lower energy consumption compared to the cloud-assisted scenario, while also eliminating bandwidth overhead associated with data transmission to the cloud.

# Summary. An optional shortened abstract.
summary: This paper integrates Edge Intelligence (EI) with the coordination language Lingua Franca (LF), using the Consistency-Availability-Latency (CAL) theorem to optimize Cyber-Physical Systems (CPS). We demonstrate an Emergency Vehicle Detection (EVD) system that prioritizes emergency vehicles through multimodal detection and LF’s deterministic coordination. Two deployment scenarios are evaluated—cloud-assisted and fully edge-based—guided by CAL tradeoffs. Experiments show that the edge-based solution reduces inference-to-actuation latency by 2.8x and energy consumption by 10.26%, while eliminating cloud bandwidth overhead.

tags:
  - Edge Intelligence
  - Lingua Franca
  - Cyber-Physical Systems

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/11106087'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://doi.org/10.1109/IPDPSW66978.2025.00175'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: "Overview of Preferential Treatment Process"
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: 
---
