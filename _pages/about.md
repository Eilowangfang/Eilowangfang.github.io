---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a Senior Engineer at Huawei, 2012 Lab. Before this, I obtained my Ph.D. degree at The Hong Kong Polytechnic University (POLYU) in 2022, under the kind and inspiring supervision of Prof. [Ken M. L. Yiu](https://www4.comp.polyu.edu.hk/~csmlyiu/) and [Zili Shao](https://www.cse.cuhk.edu.hk/people/faculty/zili-shao/). I was also fortunate to work closely with Dr. [Bo Tang](https://acm.sustech.edu.cn/btang/) and [Xiao Yan](https://yanxiaosunny.github.io/) at Southern University of Science and Technology (SUStech).



Research Interest
======
My interests are mainly database systems and data4AI, which include query optimization, AI4DB, multi-modal query processing, and data preparation for LLMs. 


Publications
======
[Speeding Up End-to-end Query Execution via Learning-based Progressive Cardinality Estimation.](https://dl.acm.org/doi/abs/10.1145/3588708?casa_token=tilBJy9JMRMAAAAA:mVyttXmuQW4bG61Jem5us18mhRYVg0tTbE9oWmO0pFNCHcd7Bl7V1pruUGgeUhdvUnG1r0bK5gfK). **Fang Wang**, Xiao Yan, Man Lung Yiu, Shuai Li, Zunyao Mao, and Bo Tang. In SIGMOD, 2023.

[Ghive: accelerating analytical query processing in apache hive via cpu-gpu heterogeneous computing.](https://dl.acm.org/doi/10.1145/3542929.3563503) Co-author. In SoCC 2022.

[Ghive: A demonstration of gpu-accelerated query processing in apache hive.](https://dl.acm.org/doi/abs/10.1145/3514221.3520166) Co-author. In SIGMOD demo 2022.

[Accelerating similarity-based mining tasks on high-dimensional data by processing-in-memory.](https://ieeexplore.ieee.org/abstract/document/9458768/) **Fang Wang**, Man Lung Yiu, and Zili Shao. In ICDE 2021.

[ReRAM-based processing-in-memory architecture for blockchain platforms.](https://dl.acm.org/doi/abs/10.1145/3287624.3287656) **Fang Wang**, Zhaoyan Shen, Lei Han, Zili Shao. In ICDE 2021.


News
------
- 01 July 2025  Moved to Shanghai, still working in Huawei.
- 12 Feb 2023   Joined Huawei Beijing, Gauss Lab.
- 16 Aug 2022   Our work LPCE (learning for cardinality estimation) is accepted by SIGMOD 2023.
- 17 June 2022  Passed the oral defense for PhD degree !!!
- 01 June 2022  Finished the internship at Huawei GuassDB as research intern for Gauss Cloud-native database project.
- 23 Dec 2020   Gave a talk on Exploiting GPUs For Database Analytical Query at Huawei GaussDB. The video recording (in Chinese) is available at Bilibili.
- 15 Sep 2020   Joined the database group as a visiting research student at Southern University of Science and Technology, China, and worked with Dr. Bo Tang.


Services
------
Reviewer: AAAI 2022/2021
Reviewer: CIKM 2021



Teaching
------
Teaching Assistant at COMP1411: Introduction to Computer Systems. Spring 2021
Teaching Assistant at COMP3021: Programming Language Paradigms. Spring 2020
Teaching Assistant at COMP5434: Big Data Computing. Summer 2019
Teaching Assistant at COMP4438: Embedded Software. Spring 2019
Teaching Assistant at COMP2121: E-Business. Fall 2018
Teaching Assistant at COMP3122: Information Systems Development. Spring 2018




Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
