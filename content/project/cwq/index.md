---
title: cal water quality .com
summary: Automated water quality reports for > 3,000 California public water systems.  
#tags: 
#  - Data science  
#  - Water
#  - Web
date: "2019-10-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
#external_link: "http://calwaterquality.com"

#header:
#  image: "cwq.png"
#  caption: "Image credit: [**Rich Pauloo**](https://www.richpauloo.com/)"

image:
  # caption:
  focal_point: Smart
  preview_only: false

# links:
# - icon: github
#   icon_pack: fab
#   name: Github
#   url: https://github.com/caccr/cawdc_2019

url_code: "https://github.com/caccr/cawdc_2019"
url_pdf: ""
url_slides: ""
#url_video: "https://www.youtube.com/watch?v=6YEkzftrbK4&t=2s"
url_project: "http://calwaterquality.com/"



# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

 

Present sources of water quality information in California (i.e. - consumer confidence reports, or CCRs) are fragmented across thousands of water utilities in the state, lack consistency and clarity, and tend to communicate data via hard-to-understand tables (see 3 examples of CCRs below, or view them in their entirely[^1].). 

{{< figure src="ccrs.png" title="CCR quality varies by water system." lightbox="true" >}}

Near-real-time, standardized, and easy to understand water quality reports would improve the public’s understanding of the water they buy and consume. Automated creation of water quality reports would ease reporting responsibilities for water agencies, freeing them to tackle harder problems.

This project aimed to build a “weather app” for California community water system water quality. The benefits of this approach include standardization, consistency across agencies, ease of use, and near-real-time water quality information.

The project aggregates publicly available water quality data for all California community water systems to report:  

* compliance status  
* chemicals detected within the past 2 years  
* average detection levels for all contaminants tested for  
* water quality indicators  
* local water and health system contact information  



[^1]: {{% staticref "files/ccr1.pdf" %}}CCR example #1{{% /staticref %}},
{{% staticref "files/ccr2.pdf" %}}CCR example #2{{% /staticref %}},
{{% staticref "files/ccr3.pdf" %}}CCR example #3{{% /staticref %}}

