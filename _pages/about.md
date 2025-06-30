---
permalink: /
title: "Juhwan Kim, Ph.D."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
🙋‍♂️ About Me
======
다양한 임베디드 시스템의 취약점을 자동 탐지하는 연구로 석/박사 학위를 취득하였으며, 현재 LIG넥스원에서 국방 무기체계의 사이버보안 아키텍처를 설계하고 있습니다. 학문적 깊이의 연구 역량과 국방 체계 개발 현장에서의 실무 경험을 결합하여, 가장 안전하고 신뢰도 높은 시스템을 구축하는 데 기여하고 있습니다.

<!-- 🎓 Education
-----
<small>
  <em>- Ph.D. in Computer and Information Security, Sejong University, Seoul</em><br>
  <em>- M.S. in Computer and Information Security, Sejong University, Seoul</em>
</small> -->

💼 Professional Experience
-----
**Senior Researcher (9+ years of experience), LIG Nex1** (2025.01 - 현재)  
<small>
  <em>- Unmanned/Intelligent Robotic Systems R&D Lab</em>
</small>

➡️ 국방 무기체계의 엔드-투-엔드(End-to-End) 사이버보안 아키텍처 설계 및 구축 담당

🚀 주요 수행 프로젝트 (Key Project)
> **프로젝트명:** 정찰용 무인수상정(USV) 체계개발사업  
> **수행기간:** 2025.01 ~ 2027.12  
> **개요:** 해군 전진기지와 주요 항만의 감시·정찰 및 현장대응 능력 강화
- **관련 기사:** [LIG넥스원, 정찰용 무인수상정 체계개발사업 수행… 399억규모](https://www.yna.co.kr/view/AKR20241219088200003)

🔬 Research Experience (2017.03 - 2024.08)
-----
**M.S. & Ph.D. in Computer and Information Security, Sejong University** 

➡️ Linux, MCU, RTOS 등 다양한 임베디드 시스템 대상 펌웨어 취약점 자동 탐지 연구 수행  
<small>
  <em>- Combined emulation techniques (firmware re-hosting based on QEMU) and software testing technologies (fuzzing, symbolic execution, etc.)</em><br>
  <em>- Discovered and reported vulnerabilities causing memory corruption and hanging in various firmware</em>
</small>

✍️ Publications
-----
### 📄 [Fuzzing of embedded systems: A survey](https://dl.acm.org/doi/abs/10.1145/3543818)

Published in ***ACM Computing Surveys***, 2022

> 임베디드 시스템 퍼징(Fuzzing) 분야의 전반적인 기술 동향과 연구 과제를 정리한 서베이 논문입니다.

**Recommended citation:** Yun, J., Rustamov, F., Kim, J., & Shin, Y. (2022). Fuzzing of embedded systems: A survey. *ACM Computing Surveys*, *55*(7), 1-33.

[**Download Paper**](/files/yun2022_survey.pdf)

 

<!-- This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
