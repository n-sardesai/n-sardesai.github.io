---
permalink: /
title: "Neil Sardesai, BA (Hons), ATCL"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! My name's Neil, and I am currently studying <b>Medicine</b> at the University of Cambridge, with an intercalated Bachelor’s degree in <b>Engineering</b>. My work sits at the intersection of medicine and technology, focusing on health data science, AI, and medical devices. I have conducted research at <b>Harvard University</b> and the <b>University of Cambridge</b>, worked in <b>medical consulting</b> — both at a global firm and freelance — and presented and published internationally.

Beyond research, I lead the <b>Cambridge University MedTech Society</b> and the <b>Cambridge University AI in Medicine Society</b>, organising events, fostering innovation, and connecting students with industry leaders. I am passionate about using technology to improve patient care, advance medical science, and bridge the gap between healthcare and engineering.

I am also deeply committed to education. As a <b>Supervisor</b> for the Cambridge Physiology and Medical Statistics courses, I support students in developing a strong foundation in these subjects. Additionally, I have delivered <b>100s of hours of tutoring</b> for medical school entry, guiding applicants through admissions tests, interviews, and applications. I also co-lead the <b>Emmanuel Widening Access Programme for Medicine</b>, working to make medical education more accessible.

Consulting
======
<ul><b>Analyst Intern</b> at Costello Medical <i>(2024)</i> </ul>
<ul><b>Research</b> at Lotus Health AI <i>(Present)</i> </ul>
<ul><b>Board Member</b> on the MeditSimple AI Ethics Advisory Board <i>(Present)</i></ul>
<ul><b>Panel Member</b> on the NIHR Cambridge Health Data Access Panel <i>(Present)</i></ul>

Talks
======

**Interview on the 'Diary of a Future CEO' Podcast**

<iframe width="560" height="315" src="https://www.youtube.com/embed/xX3UBbDnRVQ" style="border: 1px solid black;" allowfullscreen></iframe>

&nbsp

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  


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


For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
