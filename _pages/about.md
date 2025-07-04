---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!--
This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
-->

I'm currently a Research Assistant at [HKUST GREAT Smart Cities Institute](https://gsc.hkust.edu.hk/) led by Prof. [Hong Lo](https://cehklo.people.ust.hk/). I am also affiliated with the [HKUST Intelligent Transportation Systems Lab](https://sites.google.com/view/hkustits/home). Previously, I was also an RA at the Department of Applied Mathematics, PolyU HK, working with Prof. [Guohao Shen](https://ghshen1.github.io/). I obtained my MPhil at HKUST advised by Prof. [Tong Zhang](https://tongzhang-ml.org/) and B.S. Applied Math at the University of the Philippines. Broadly, my research interests are in the applications of AI to engineering and social problems. Specifically, I am interested in transportation, computer vision, human-AI interaction, and uncertainty quantification.

## News
<!--  
- A paper is accepted at the 29th International Conference of Hong Kong Society for Transportation Studies.
- A paper on Transportation AI is accepted at the International Conference on Computer Vision (ICCV) 2025 Workshop. Preprint will be released soon.
- A paper on Frequency Domain Uncertainty Quantification is accepted at the International Conference on Computer Vision (ICCV) 2025, Workshop on Advanced Perception for Autonomous Healthcare (APAH). Preprint will be released soon.
-->
- **2025-06-05:** Our AAMAS paper on conformal set-based human-AI complementarity is now published at the [ACM Digital Library](https://dl.acm.org/doi/10.5555/3709347.3743792).
- **2025-04-02:** I started work at the HKUST GREAT Smart Cities Institute in collaboration with [Suntec Innovations](https://www.suntec.app/) under an AI project funded by [Hong Kong Smart Traffic Fund](https://stf.hkpc.org/cs-87-2403-ra/). We aim to use real-time data to give drivers AI assistance insights map which suggests locations with maximised trip profitability.
- **2024-12-16:** A first-author paper entitled "Conformal Set-based Human-AI Complementarity with Multiple Experts" is accepted at [AAMAS 2025](https://aamas2025.org/) as Full Paper (Oral Presentation) (_acceptance rate = 25%_). Preprint version and code will be released soon.
- **2024-01-31:** A first-author work "MEDL-U: Uncertainty-aware 3D Automatic Annotation based on Evidential Deep Learning" is accepted at ICRA 2024. Our collaborator, Autowise, wrote a [blog post](https://autowise.ai/en/2024/05/13/autowise-icra2024-paper/) about our work.
- **2023-12-30:** I finished my MPhil CSE at HKUST.

### Hobbies
I love reading books while commuting. Currently I am reading the following books:
- The Logic of Scientific Discovery
- Introduction to Mathematical Philosophy
- The Lean Startup
- Called to Greatness
- The Elements of Programming Style

Finished:
- The Structure of Scientific Revolutions
- Co-Intelligence: Living and Working with AI
- Zero to One
- A Mind for Numbers
- The Case for Faith
- Relentless
- Thinking Fast and Slow
- The Psychology of Money
- Growing Deep in Faith
