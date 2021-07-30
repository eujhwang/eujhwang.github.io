---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a software engineer working on knowledge base at Naver Corp. 
Previously, I completed my MS in Computer Science at UMass Amherst and completed my Bachelor's at Kwangwoon University. 

I'm particularly interested in graph structured data with graph neural networks or knowledge graphs and understanding raw texts.
Ultimately, I would like to develop a simple yet efficient model that can be easily applied to industry with a decent performance.

My most recent works are focused on relation extraction and question answering using geometric embedding and graph neural networks.
I primarily worked with members at Information Extraction and Synthesis Laboratory (IESL) on geometric embedding and IBM Research on Graph neural networks.

[CV](https://eujhwang.github.io/files/eunjeong_research_cv.pdf)


Publications
------
1. Revisiting Virtual Nodes in Graph Neural Networks for Link Prediction (Under Review at NeurIPS 2021)\
   **Eunjeong Hwang**, Anonymous 
2. Interdependency between the stock market and financial news (IEEE BigData2019 workshop)\
   **Eunjeong Hwang**, Yong-Hyuk Kim 

Projects
------
**Joint constrained learning using box embedding**\
 Implemented relation extraction model using box embedding. 
 Effectively reduced violated constraints in relations labels, which is much better than our baseline vector models.

**Virtual node augmented graph neural networks for link prediction**\
 Implemented virtual node model with graph neural networks for link prediction tasks on Open Graph Benchmark (OGB) datasets.
 Our model outperformed not only standard GNN models, such as GCN, SAGE, and GIN, but also recent complex models, such as Position aware-GNN and APPNP.  
 Under review at NeurIPS 2021.

**Question answering on knowledge graph using box embedding**\
  Implemented question answering model by embedding queries as probabilistic boxes using gumbel distribution.
  Our model was more mathematically explainable than Query2Box model and produced similar performance.

**Interdependency between stock market and financial news articles**\
  Analyzed the interdependency between stock market and financial articles using sentiment analysis. 
  Discovered trends that stock prices respond to social issues before the articles do. 
  Published IEEE BigData 2019 workshop
  
Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
