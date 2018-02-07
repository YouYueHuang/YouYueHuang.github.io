---
layout: post
title:  "You are not machine"
date:   2017-12-21
desc: "The difference between Cluster and Segmentation in concept"
keywords: "data mining, clustering"
categories: [machinelearning]
tags: [data mining, clustering]
icon: icon-machine-learning
---

<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://www.w3schools.com/lib/w3-theme-black.css">

<div class="w3-twothird w3-container">
  <h1 class="w3-text-teal">The difference of Cluster and Segmentation</h1>
  <p><b>Segmentation</b> 
    <br>Decide on the criteria (actually on the borders between the segments) and assign each customer to its segment.
  </p>
  <p><b>Clustering</b>
    <br>Find regions in a (one- or multi-dimensional) space with a different density of items than the neighboring regions.
      "finding regions" means : finding the borders between the regions, because it is only if you know where the borders are that you can say where the region is situated.
  </p>
  <p><b>Conclusion</b> 
    <br>Clustering is finding borders between groups, and segmenting is using borders to form groups.
  </p>
  <p><b>Comparason</b>
    <ul>
      <li>Segmentation is always possible, even in an extremely homogeneous collection of items.  You just decide where you will cut between the groups.</li>
      <li>Finding clusters in a extremely homogeneous collection is impossible, since by definition there are no density differences, and hence no clusters to find.</li>
    </ul>
  </p>
</div>
