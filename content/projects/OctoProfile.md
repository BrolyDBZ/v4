---
date: '2023-01-15'
title: 'Distributed MapReduce'
github: 'https://github.com/bchiang7/octoprofile'
external: 'https://octoprofile.now.sh'
tech:
  - Golang
  - RPC
showInProjects: true
---

Implemented a Distributed MapReduce with a master process that hands out tasks to workers and copes with failed workers, and a worker process that calls application Map and Reduce functions and handles reading and writing files.

Build something similar to the paper [MapReduce paper](http://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf).
