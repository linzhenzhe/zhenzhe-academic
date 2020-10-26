---
title: "WiEat: Fine-grained Device-free Eating Monitoring Leveraging Wi-Fi Signals"
authors:
- Zhenzhe Lin
- Yucheng Xie
- Xiaonan Guo
- Yanzhi Ren
- Yingying Chen
- Chen Wang
date: "2020-08-03T00:00:00Z"
doi: "10.1109/ICCCN49398.2020.9209628"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2020 29th International Conference on Computer Communications and Networks (ICCCN)*
publication_short: In *ICCCN 2020*

abstract: Eating well plays a key role in people’s overall health and wellbeing. Studies have shown that many health-related problems such as obesity, diabetes and anemia are closely associated with people’s unhealthy eating habits (e.g., skipping meals, eating irregularly and overeating). Thus, keeping track of diet is becoming more important. Traditional eating monitoring solutions relying on self-report remain an onerous task, while the recent trends requiring users to wear dedicated yet expensive hardware are cumbersome. To overcome these limitations, in this paper, we develop a device-free eating monitoring system using WiFi-enabled devices (e.g., smartphone or laptop). Our system aims to automatically monitor users’ eating activities by identifying the fine-grained eating motions and detecting the minute movements during chewing and swallowing. In particular, our system distinguishes eating from non-eating activities by using K-means clustering with principal component analysis on the extracted Channel State Information (CSI) from WiFi signals. It further adopts a soft decision-based eating motion classification through identifying the utensils (e.g., using a folk, knife, spoon or bare hands) in use. Moreover, we propose a minute motion reconstruction method to identify chewing and swallowing through detecting users’ minute facial muscle movements. The derived fine-grained eating monitoring results are beneficial to the understanding of users’ eating behaviors and estimation of food intake types and amounts. Extensive experiments with 20 users over 1600-minute eating show that the proposed system can recognize the user’s eating motions with up to 95% accuracy and estimate the chewing and swallowing amount within 10% percentage error.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: "paper/09209628.pdf"
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

