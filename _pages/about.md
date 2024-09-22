---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Here is **Yijian Lu (Lucas, 呂奕鑒)**. I am currently a year-one Ph.D student in Tsinghua University, supervised by Prof. [Juanzi Li](https://keg.cs.tsinghua.edu.cn/persons/ljz/) and supported by [Hong Kong Jockey Club](https://jcscholarships.hk/en). Before that, I received my M.Phil degree in Computer Science from The Chinese University of Hong Kong in 2024, supervised by Prof. [Irwin King](https://scholar.google.com/citations?user=MXvC7tkAAAAJ&hl=en). In 2022, I received my Bachalor's degree in Computer Science from CUHK as well. 
<br>My research interest is Natural Language Processing, specifically including Large Language Model, Text Watermarking, LLM Safety and Fact-checking.

📧 Contact
-----
Please feel free to contact me via **luyj24@mails.tsinghua.edu.cn**

🆕 News and Updates
======
- **2024.08:** 🎉🎉 Excited to announce the our paper: [“A Survey of Text Watermarking in the Era of Large Language Models”](https://survey-text-watermark.github.io/index.html) is accepted by [ACM Computing Surveys](https://dl.acm.org/journal/csur)!
- **2024.08:** Glad to serve as a reviewer for [ICLR 2025](https://iclr.cc/)
- **2024.07:** Glad to serve as a reviewer for [ICONIP 2024](https://iconip2024.org/)
- **2024.05:** 🎉🎉 Passed my M.Phil oral defense with the topic "Text Watermarking in the Era of Large Language Models: Enhancement and Extension"
- **2024.05:** Invited to serve as a reviewer for [NeurIPS 2024](https://neurips.cc/)
- **2024.05:** 🎉🎉 My paper ["An Entropy-based Text Watermarking Detection Method"](https://aclanthology.org/2024.acl-long.630/) has been accepted to [ACL 2024](https://2024.aclweb.org/) Main Conference! 

📚 Selected Publications
======
- An Entropy-based Text Watermarking Detection Method [[ACL 2024]](https://aclanthology.org/2024.acl-long.630/)
- A survey of text watermarking in the era of large language models [[ACM]](https://arxiv.org/abs/2312.07913) [[Webpage]](https://survey-text-watermark.github.io/index.html)
- MarkLLM: An Open-Source Toolkit for LLM Watermarking [[Arxiv]](https://arxiv.org/abs/2405.10051)
- WaterSeeker: Efficient Detection of Watermarked Segments in Large Documents [[Arxiv]](https://arxiv.org/abs/2409.05112)

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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
