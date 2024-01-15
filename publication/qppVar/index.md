---
title: "Information Needs, Queries, and Query Performance Prediction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Anna Shtok
- Fiana Raiber
- Oren Kurland
- J. Shane Culpepper

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-07-01T00:00:00Z"
doi: "10.1145/3331184.3331253?cid=99659451812"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of the 42nd International ACM SIGIR Conference on Research and Development in Information Retrieval
publication_short: In *SIGIR'19*

abstract: 'The query performance prediction (QPP) task is to estimate the effectiveness of a search performed in response to a query with no relevance judgments. Existing QPP methods do not account for the effectiveness of a query in representing the underlying information need. We demonstrate the far-reaching implications of this reality using standard TREC-based evaluation of QPP methods: their relative prediction quality patterns vary with respect to the effectiveness of queries used to represent the information needs. Motivated by our findings, we revise the basic probabilistic formulation of the QPP task by accounting for the information need and its connection to the query. We further explore this connection by proposing a novel QPP approach that utilizes information about a set of queries representing the same information need. Predictors instantiated from our approach using a wide variety of existing QPP methods post prediction quality that substantially transcends that of applying these methods, as is standard, using a single query representing the information need. Additional in-depth empirical analysis of different aspects of our approach further attests to the crucial role of query effectiveness in QPP.'


# Summary. An optional shortened abstract.
# summary: 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'qppVar.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/Bn4Evp2qguo'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
