---
title: 'A Generative AI-Driven Architecture for Intelligent Transportation Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Fabrizio Mangione
  - admin
  - Claudio Savaglio
  - Giancarlo Fortino

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-10-11T00:00:00Z'
doi: 'https://doi.org/10.1109/SMC53992.2023.10393907'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-11T00:00:00Z'

# Publication type.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: 2024 IEEE 10th World Forum on Internet of Things (WF-IoT)
publication_short: ""

abstract: The rapid acceleration of urbanization underscores the urgent need for developing intelligent transportation systems (ITS) to enhance the efficiency, safety, and sustainability of urban mobility. Within this context, accurately predicting vehicle trajectories is paramount for facilitating superior traffic management and control. To this end, the paper presents an innovative architecture that combines a Long Short-Term Memory (LSTM) module with a generative artificial intelligence (Gen-AI) component, specifically the RoBERTa Transformer model. By leveraging these sophisticated architecture, the LSTM network with a recursive decoder outperforms the teacher forcing decoder on clean datasets, showing higher robustness in time-series predictions. When video data was partially missing, performance decreased, but using the RoBERTa model to reconstruct the missing data significantly improved results for both decoders (from 37% up to 92%). The reconstructed data notably enhanced the performance of the LSTM models, particularly when larger portions of the video data were absent. These findings highlight the effectiveness of data reconstruction techniques in mitigating the challenges posed by uncontrollable events (common in real ITS scenarios) which can bear to incomplete information.

# Summary. An optional shortened abstract.
summary: This paper addresses the need for intelligent transportation systems (ITS) by proposing an innovative architecture for vehicle trajectory prediction. It integrates a Long Short-Term Memory (LSTM) module with a generative AI component, specifically the RoBERTa Transformer model. The LSTM network with a recursive decoder outperforms a teacher forcing decoder on clean datasets, demonstrating higher robustness in time-series predictions. When video data is partially missing, performance drops, but RoBERTa-based data reconstruction significantly improves results (from 37% to 92%). These findings emphasize the importance of data reconstruction in handling incomplete information in real-world ITS scenarios.

tags:
  - Digital Twin

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10393907'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/abstract/document/10393907?casa_token=xPGx2_qCCP8AAAAA:ke3_oxXZLehLpnHpfZHlKE5D08F4KwYrg6nXU8Bmt-OQgg2DOyxeY-0prk31CJRo5SuGN4WmfY__'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
  # caption: 'Proposed approach: from the PO ś and its DT ś to its signature, in which features are "opportunistically" selected and synthetically elaborated' 
  #'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  # focal_point: ''
  # preview_only: false

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
