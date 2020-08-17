## Research tools repository

This repository holds an overview of research tools and their status analogous to [this page](https://brightspace-support.tudelft.nl/educational-tooling/) for educational tools. This is work-in-progress and mostly useful to see how such an overview would look, but also as a test to start creating the actual list. Also this repository is used to test a viable workflow for maintaining the list

### Website

Changes made to this repository will automatically be incorporated into the website at https://tudelft-innovation.github.io/


### Workflow

A definite workflow has not yet been established. For now you can clone this repository, make your changes, and submit a merge request.

### Adding and editing tools

All tools are described by a file in the docs/_research_tools directory. 
Each file is a jekyll markdown file that needs to contain [front matter](https://jekyllrb.com/docs/front-matter/) describing the name, status and category of the tool. For instance, the markdown file for Dropbox looks like this:
```
---
status: Gray
name: Dropbox
category: Collaboration
---
Recommended alternatives: M365 OneDrive, Sharepoint, SURFdrive, MS Teams
```

The three dashes serve to distinguish the front-matter variables from the actual text of the description.

The name of the file is of no consequence, but for sanity's sake please name it the same as the tool that it describes!
