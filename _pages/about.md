---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Dr. Wei REN is Postdoc Fellow at Department of Computing, The Hong Kong Polytechnic University.  

Dr. Wei REN received a B.S. degree in  Measurement, Control Technology and Instruments from Tsinghua University (THU), Beijing, China, in July, 2015. He received a PhD degree in Information and Communication Engineering from Beijing Institute of Technology supervised by [Prof. Quanhua Liu](https://radar.bit.edu.cn/szdw/jsfc/gjjrc/7a076c3d6a0042279d6804ed128e9c8b.htm) and [Prof. Erke Mao](https://radar.bit.edu.cn/szdw/jsfc/ys/0ece10fa1a6f42cab3b578385a295524.htm) in Dec., 2021. He was also a visiting PhD student with Department of Electrical Engineering and Computer Science, The University of Tennessee, Knoxville (UTK) from 2019 to 2020, supervised by [Prof. Aly E. Fathy](https://microwave.utk.edu/people/aly-fathy/).

**Research Interests:** Signal Processing, Radar Waveform Design,  BioRadar and Biomedical Applications

**Email:** [weiren_thu@163.com](weiren_thu@163.com) OR [wrthu2011@gmail.com](wrthu2011@gmail.com)

Latest News
======
- **Dec. 2024** Our paper titled **Noncontact Multi-Point Vital Sign Monitoring With mmWave MIMO Radar** is accepted by IEEE Transactions on Microwave Theory and Techniques (TMTT). [link](https://arxiv.org/abs/2411.09201)
- **Nov. 2024** I serve as the Session Chair (Session: Radar Data and Information Processing) in IEEE International Conference on Signal, Information and Data Processing (ICSIDP) 2024. [link](https://www.icsidp.org/index.asp).
- **Nov. 2024** I give a talk at Shenzhen Univeristy. The title is **Non-Contact Vital Sign Monitoring of High DoF individuals**. Thank you very much from the invitation from [Prof. Shengli ZHANG](https://ceie.szu.edu.cn/info/1014/1495.htm).  

Publications
======
### Wireless Human Sensing
- [Noncontact Multi-Point Vital Sign Monitoring With mmWave MIMO Radar](https://arxiv.org/abs/2411.09201), **Wei Ren**, Jiannong Cao, Huansheng Yi, Kaiyue Hou, Miaoyang Hu, Jianqi Wang, Fugui Qi, ***IEEE Transactions on Microwave Theory and Techniques (TMTT)***, 2024. (Accepted)
- [Tracking-Aided Respiration Detection Using Radar During Large-Scale Body Movements](https://ieeexplore.ieee.org/abstract/document/10159563), **Wei Ren**, Huizi Han, Shaoqiang Chang, Quanhua Liu, ***IEEE Sensors Journal***, 2023.
- 


### Radar Waveform Design ###
- [Design of Polyphase Sequence Sets with Good Correlation Properties under Spectral Distortion via Majorization-Minimization Framework](https://www.sciencedirect.com/science/article/abs/pii/S1051200423003792), Changjie Wang, Hao Zhang, **Wei Ren<sup>*</sup>**, Quanhua Liu, ***Digital Signal Processing (DSP)***, 2024

### Interference and clutter suppression ###
- [Improving Range Ambiguity Suppression in Pulse-Doppler Radar Systems with Nonlinear Processing and Joint Reversible Mismatch Filtering](https://ieeexplore.ieee.org/abstract/document/10266747), Yuanshuai Li, **Wei Ren<sup>*</sup>**, Fawei Yang, Kaixiang Zhang, Quanhua Liu, Aly E. Fathy, ***IEEE Transactions on Radar Systems***, 2023

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
