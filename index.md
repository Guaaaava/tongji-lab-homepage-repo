---
---

# 这是同济大学“人工智能+大气海洋”实验室的首页



{% include section.html %}

## 实验室介绍

{% capture text %}

这里是同济大学“人工智能+大气海洋”实验室的研究内容介绍。

{%
  include button.html
  link="research"
  text="查看实验室研究内容和成果"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="研究内容"
  text=text
%}

{% capture text %}

这里是同济大学“人工智能+大气海洋”实验室的研究项目介绍。

{%
  include button.html
  link="projects"
  text="查看实验室项目"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="研究项目"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

这里是同济大学“人工智能+大气海洋”实验室的研究团队介绍。

{%
  include button.html
  link="team"
  text="查看研究团队"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="研究团队"
  text=text
%}
