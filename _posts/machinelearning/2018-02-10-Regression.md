---
layout: post
title:  "Regression"
date:   2018-02-10
desc: "The framework of regression in machine learning"
keywords: "regression"
categories: [machinelearning]
tags: [regression]
icon: icon-machine-learning
---

<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://www.w3schools.com/lib/w3-theme-black.css">

<!-- img_path: /YouYueHuang.github.io/static/assets/img/blog  -->

<div class="w3-twothird w3-container">
  <h1 class="w3-text-teal">Regression</h1>
  <p>Regreesion is a approach to estimate the relationships among variables, and the target variable is a continuous number.</p>
  <img src="{{ site.img_path }}/blog_machine_learning/RSS.gif" width="100%">
  <img src="{{ site.img_path }}/blog_machine_learning/optimize_func.gif" width="100%">
  <p>The goal is to find a set of weight and bias to minimize the loss function, which makes the residual sqaure of sum the minimum</p>
  <p>We have to define a good loss function, which is differentiable, then we can use gradient descent to find global optimum</p> 
  <p>If the fitting line cost too much error, we should adopt high order features or increase the model complexity to reduce the error</p> 
  <p><b>Application</b> 
    <ul>
      <li>Stock price prediction</li>
      <li>Input: past stock price, time, seasonality, related news</li>
      <li>Output: future stock price</li>
    </ul>
    <ul>
      <li>Self-driving car control</li>
      <li>Input: front view, lane line, desination</li>
      <li>Output: the angle of steering wheel</li>
    </ul>
    <ul>
      <li>Recommender system / </li>
      <li>Input: demographics, the features of product, popularity of the product</li>
      <li>Output: the probability of buying products/list of ranked items</li>
    </ul>
    <ul>
      <li>Online advertisement display</li>
      <li>Input: the tag of user historical records, context, </li>
      <li>Output: advertisement</li>
    </ul>
  </p>
</div>
