---
title: 'Engineering Opportunistic Digital Twins with Lingua Franca'

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

date: '2025-11-27T00:00:00Z'
doi: 'https://doi.org/10.1016/j.future.2025.108262'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-11-27T00:00:00Z'

# Publication type.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: Future Generation Computer Systems
publication_short: ""

abstract: >
Digital Twins (DTs) have emerged as essential tools for virtualizing and enhancing Cyber-Physical Systems (CPS) by providing synchronized digital counterparts that enable monitoring, control, prediction, and optimization. Initially conceived as passive digital shadows, DTs are increasingly evolving into intelligent and proactive entities, enabled by the integration of Artificial Intelligence (AI). Among these advancements, Opportunistic Digital Twins (ODTs) represent a novel class of DTs\: living, AI-aided, and actionable models that *opportunistically* exploit edge–cloud resources to deliver enriched and adaptive representations of physical entities and processes. However, despite their promise, current research lacks systematic engineering methods to ensure reliable coordination, determinism, and real-time responsiveness of ODTs in distributed and resource-constrained CPS. This article addresses this gap by introducing an engineering approach to build dependable and efficient ODTs by leveraging the deterministic concurrency, explicit timing semantics, and disciplined event handling of **Lingua Franca (LF)**. The approach is exemplified through a Smart Traffic Management case study centered on Emergency Vehicle Preemption (EVP), where the ODT dynamically selects AI models based on runtime conditions while ensuring deterministic coordination across distributed nodes. Experimental results confirm the feasibility and effectiveness of our methodology, underscoring the potential of LF-based ODT engineering to enhance reliability, adaptability, and scalability in intelligent and distributed CPS deployments.

# Summary. An optional shortened abstract.
summary: Digital Twins (DTs) are evolving from passive digital shadows into intelligent and adaptive systems empowered by AI. This work focuses on Opportunistic Digital Twins (ODTs), a new class of DTs that dynamically exploit edge–cloud resources to enhance the representation and control of Cyber-Physical Systems (CPS). We introduce an engineering approach for building dependable ODTs using the deterministic concurrency and explicit timing semantics of Lingua Franca (LF). A Smart Traffic Management case study on Emergency Vehicle Preemption (EVP) demonstrates how ODTs can adapt model selection at runtime while preserving deterministic coordination across distributed nodes. Results show that LF-based ODTs improve reliability, adaptability, and scalability in intelligent CPS deployments.

tags:
  - Digital Twin
  - Cyber-Physical Systems
  - Lingua Franca
  - Edge Intelligence

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/pii/S0167739X25005564?via%3Dihub#fig0001'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.sciencedirect.com/science/article/pii/S0167739X25005564?via%3Dihub#fig0001'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'ODT engineering workflow: perception via Sensing and Synthetic Sensing; (Opportunistic) Service Provisioning; Simulation with LF-based formal verification under CAL-guided analysis; and Deployment.' 
  #'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
