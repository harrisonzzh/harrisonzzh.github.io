---
title: "Similated Self Driving Car"
excerpt: "This project is building a self-driving program to drive a car on the Unity simulater <br/><img src='/images/project_self_driving_preview.png' height='100'>"
collection: portfolio
---

## Description

This project is building a self-driving program to drive a car on the Unity simulater ([link](https://github.com/blog/1395-relative-links-in-markup-files)).
The project used Nvidia self-driving car CNN architecture ([paper](https://images.nvidia.com/content/tegra/automotive/images/2016/solutions/pdf/end-to-end-dl-using-px.pdf))
and implemented with Tensorflow/Keras. <br /><br />

|Mountain Track|
|:------------:|
|<img src="/images/project_self_driving_test.png" alt="alt text" width="600" height="whatever">|
|[YouTube Link](https://www.youtube.com/watch?v=O75wfU4zAiU)|


### Prerequisites

Build a virtual enviroment in order to run the project: <br />
```python
## Use TensorFlow without GPU
conda env create -f environment.yml 

## Use TensorFlow with GPU
conda env create -f environment-gpu.yml
```
<br />

### Workflow Diagram
<img src="/images/project_self_driving_report.jpeg" alt="alt text" width="800" height="whatever">