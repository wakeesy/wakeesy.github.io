---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm Ke Wang, a student majoring in computer science and technology at Yunnan University. During my undergraduate studies, I excelled in my studies and was ranked in the top of my specialty in terms of grades and overall assessment. 

Additionally, I am proficient in c++ and python, actively participated in algorithm competitions and won the national silver medal in the ACM-ICPC National Collegiate Programming Contest. 

I also took part in scientific research and study vigorously, and published a paper(JCR Q2, first author) in the field of remote sensing image small target detection under the guidance of my undergraduate teacher. Meanwhile, I engaged in a Zhejiang University research training program, reading papers and practicing multimodal models, and proposed improvements to the existing multimodal mobile application agent model with a single evaluation metric. 

In my subsequent studies and research, I also would like to do more in-depth research in computer vision and multimodal modeling.

Education
======
- 2021.09 - 2025.06, &nbsp;&nbsp;&nbsp; B.S. in Computer Science and technology, &nbsp;&nbsp;&nbsp; Yunnan University

Publications
======
## RN-YOLO: A Small Target Detection Model for Aerial Remote-Sensing Images

Published in *Electronics* ***(JCR Q2)***

***Main Work:*** Based on the challenges of remote-sensing image target detection tasks with complex backgrounds, large scale spans, and numerous small targets, we respectively improved the feature extraction network, feature fusion network, and detection head of YOLOv8 to enhance the detection precision while reducing the model parameters. In the research, I independently complete model modification experiments and paper writing.

Recommended citation: ***Wang K***, Zhou H, Wu H, et al. RN-YOLO: A Small Target Detection Model for Aerial Remote-Sensing Images[J]. Electronics, 2024, 13(12): 2383.  

Competitions
======
[1] ACM-ICPC International Collegiate Programming Contest &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; National silver medal &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2023.06

[2] 第十五届全国大学生数学竞赛 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 省级一等奖 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2023.12

[3] 中国高校计算机大赛-团体程序设计天梯赛 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 省级一等奖 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2023.05

[4] 第二十届百度之星程序设计大赛 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 省级一等奖 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2024.06

[5] 第九届云南省“互联网+”创新创业大赛 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 省级金奖 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2023.08

Research trainings
=====
[1] A Comprehensive Evaluation for Model Efficiency and Accuracy in Multimodal Mobile App Agent &nbsp;&nbsp;&nbsp; Zhejiang University &nbsp;&nbsp;&nbsp; 2024.01~2024.06

***Main Work:*** Most of the evaluation metrics for multimodal mobile application agent models only focus on the accuracy or the score of the model, but both of them have their own shortcomings. Therefore, based on the "accuracy" and "score", we proposed several different evaluation indexes for accuracy under different task types. In addition, since the current model lacks the efficiency evaluation, a new evaluation index is raised for model efficiency.



<!-- This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
