---
permalink: /
title: "About the Lab"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Mauris vitae ultricies leo integer malesuada. Vulputate ut pharetra sit amet aliquam id diam maecenas. Posuere sollicitudin aliquam ultrices sagittis orci a scelerisque purus. Et tortor at risus viverra adipiscing at in. Urna nunc id cursus metus aliquam eleifend. Massa tincidunt dui ut ornare lectus. Rutrum tellus pellentesque eu tincidunt tortor aliquam nulla facilisi cras. Enim diam vulputate ut pharetra sit. Facilisi cras fermentum odio eu feugiat pretium. Commodo elit at imperdiet dui accumsan sit amet nulla. Volutpat maecenas volutpat blandit aliquam etiam erat velit scelerisque. Vivamus at augue eget arcu dictum varius duis. Faucibus pulvinar elementum integer enim neque volutpat. Duis tristique sollicitudin nibh sit amet commodo nulla facilisi.

Cras adipiscing enim eu turpis. Imperdiet massa tincidunt nunc pulvinar sapien et ligula ullamcorper. Sed lectus vestibulum mattis ullamcorper velit. Ut faucibus pulvinar elementum integer. Mattis nunc sed blandit libero volutpat sed cras ornare. Diam volutpat commodo sed egestas egestas fringilla phasellus faucibus. Risus nullam eget felis eget nunc lobortis mattis. In tellus integer feugiat scelerisque varius morbi enim. Eget nunc lobortis mattis aliquam faucibus purus in. Ut pharetra sit amet aliquam id diam maecenas ultricies mi. Augue neque gravida in fermentum et sollicitudin ac orci. Id donec ultrices tincidunt arcu non. Pharetra et ultrices neque ornare aenean euismod. Purus faucibus ornare suspendisse sed. Nibh tellus molestie nunc non blandit massa enim. Non diam phasellus vestibulum lorem sed risus. Vel eros donec ac odio tempor orci dapibus ultrices in. Libero id faucibus nisl tincidunt

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
