---
title: "EOSAFE: Security Analysis of EOSIO Smart Contracts"
authors:
- Ningyu He
- admin
- Haoyu Wang
- Lei Wu
- Xiapu Luo
- Yao Guo
- Ting Yu
- Xuxian Jiang

# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2021-04-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-04-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *USENIX Security Symposium*
publication_short: In *USENIX Security 2021*

abstract: The EOSIO blockchain, one of the representative Delegated Proof-of-Stake (DPoS) blockchain platforms, has grown rapidly recently. Meanwhile, a number of vulnerabilities and high-profile attacks against top EOSIO DApps and their smart contracts have also been discovered and observed in the wild, resulting in serious financial damages. Most of the EOSIO smart contracts are not open-sourced and typically compiled to WebAssembly (Wasm) bytecode, thus making it challenging to analyze and detect the presence of possible vulnerabilities. In this paper, we propose EOSAFE, the first static analysis framework that can be used to automatically detect vulnerabilities in EOSIO smart contracts at the bytecode level. Our framework includes a practical symbolic execution engine for Wasm, a customized library emulator for EOSIO smart contracts, and four heuristic-driven detectors to identify the presence of the four most popular vulnerabilities in EOSIO smart contracts. Experiments have shown that EOSAFE achieves promising results in detecting vulnerabilities, with an F1-measure of 98%. We have applied EOSAFE to all active 53,666 smart contracts in the ecosystem (as of November 15, 2019). Our results show that over 25% of the smart contracts are labeled vulnerable. We further analyze possible exploitation attempts on these vulnerable smart contracts and identify 48 in-the-wild attacks (27 of them have been confirmed by DApp developers), which have resulted in financial loss of at least 1.7 million USD.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
pages: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://sec21fall.usenix.hotcrp.com/doc/sec21fall-final497.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
