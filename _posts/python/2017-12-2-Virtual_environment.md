---
layout: post
title:  "Build a virtual environment of Python"
date:   2017-12-21
desc: "Build a virtual environment of Python"
keywords: "virtual environment, package management"
categories: [python]
tags: [virtual environment, package management]
icon: icon-python
---

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/2.0-latest/MathJax.js?config=TeX-MML-AM_HTMLorMML-full"> </script>
<p>
\(ax^2 + bx + c = 0\) and they are
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$
</p>

A Virtual Environment is a tool to keep the dependencies required by different projects in separate places.

1. Check `anaconda` is installed and in your PATH
2. Open a terminal client.
3. Check if it is installed successfully with `conda -V`. If conda is installed you should see current Anaconda version.
4. Create a virtual environment for your project with `conda create -n yourenvname python=x.x anaconda`

In the terminal client enter `yourenvname`, which is the name you want to call your environment, and replace x.x with the Python version you wish to use. (You can see a list of available python versions with `conda search ^python$`.

This will install the Python version and all the associated anaconda packaged libraries at `path_to_your_anaconda_location/anaconda/envs/yourenvname`.
