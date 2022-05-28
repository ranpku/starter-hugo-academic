---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "SSR: Joint Optimization of Recommendation and Adaptive Bitrate Streaming for Short-form Video Feed"
authors: ["admin","Yuanxing Zhang","Wenhan Zhang","Kaigui Bian"]
date: 2022-12-18
doi: "10.1109/MSN50589.2020.00074"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-05-28T11:42:51+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE 16th International Conference on Mobility, Sensing and Networking"
publication_short: In *MSN*

abstract: "Short-form video feed has become one of the most popular ways for billions of users to interact with content, where users watch short-form videos of a few seconds one-by-one in a session. The common solution to improve the quality of experience (QoE) for short-form video feed is to treat it as a common sequential item recommendation problem and maximize its click-through rate prediction. However, the QoE of short-form video streaming under dynamic network conditions is jointly determined by both recommendation accuracy and streaming efficiency, and thus merely considering recommendation will lead to the degradation of the QoE of the streaming system for the audience. In this paper, we propose SSR, namely the short-form video streaming and recommendation system, which consists of a Transformer-based recommendation module and a reinforcement learning (RL) based bitrate adaptation streaming module. Specifically, we use Transformer to encode the session into a representation vector and recommend proper short-form videos based on the user's recent interest and the timeliness characteristics of short-form video contents. Then, the RL module combines the representation of session and other observations within the playback, and yields the appropriate bitrate allocation for the next short-form video to optimize a given QoE objective. Trace-driven emulations verify the efficiency of SSR compared to several state-of-the-art recommender systems and streaming strategies with at least 10%-15% QoE improvement under various QoE objectives."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

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
