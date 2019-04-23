---
title: Network
author: Florian Rämisch
layout: page
---

## Open Source Software

In this project we have a strong focus on software development. A lot of code is and was written. We try to package it into tools and reusable software components. On this page you find all tools which are already released. Until the end of 2019 we will work on the code actively. Further development depends on the success of our funding efforts. 

## Tools 

* [provit](https://github.com/diggr/provit)
* [passable youtube grabber](https://github.com/diggr/pyg)
* [diggrtoolbox](https://github.com)
* kørby
* daft

### provit

*provit* is a lightweight, dezentralized provenance tracking framework. It allows
the user to track workflows and modifications of data and files. It works completely decentralized, all information is stored in .prov files (as JSON-LD RDF graphs) along it's corresponding data file in the file system. No central database or server setup is needed.  

We are using the [PROV-O vocabulary](https://www.w3.org/TR/prov-o/) which is standardized by the [W3C](https://www.w3.org). Our aim is to provide an easy to use interface for users who have never worked with provenance tracking before.  

[Learn more](//tools/provit)
[Download, use and improve](https://github.com/diggr/provit)

### passable youtube grabber

*pyg* is a batch downloader for youtube (meta)data such as comments, channels, subscribers, etc. It was originally designed and build for cultural scientists who study the reception of video games in the comments section below the videos of *Gaming Influencers*. 

It can be used to fetch Youtube data (metadata for videos, playlists, comments and captions) for channels as well as for collections of videos. This data is stored in zip files. They can be upgraded easily, which is especially useful when investigating current action in large channels or networks. The data can be exported to Elasticsearch for further analysis (videos and comments). Networks of related channels or recommended videos can be generated and saved for further processing e.g. in Gephi. 

[Learn more](//tools/pyg)
[Download, use and improve](https://github.com/diggr/pyg)

### diggrtoolbox

We collected our often used helper functions into this library. We use it in our tools, but also want to provide some collection of functions for people working with data. As its applicablility outside our working group might be very limited, we hope that you at least find some ideas useful.

[Learn more](//tools/diggrtoolbox)
[Download, use and improve](https://github.com/diggr/diggrtoolbox)
