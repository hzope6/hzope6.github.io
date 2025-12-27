---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit:  # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: false # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I’m a **graduating MS/BS student** in Computer Science at Stanford University, where I do research in the **Stanford NLP Group** ([Social and Language Technologies Lab](https://saltlab.stanford.edu)) under Diyi Yang. My prior work has focused on large language model alignment and evaluation, with a broader interest in how AI systems reason, collaborate, and interact with people.

This summer, I was at **Microsoft Research**, where I worked on [improving LLM reasoning capabilities](https://www.arxiv.org/abs/2509.22979) through post-training and test-time scaling with domain-specific knowledge. I also co-led [Future of Work with AI Agents](https://arxiv.org/abs/2506.06576) at Stanford, research which developed a novel framework for evaluating human–AI collaboration potential and quantifying misalignment between human needs and AI capabilities across diverse domains. My work has been featured in Forbes, Stanford HAI, and Yahoo Finance.

I’ve also spent time in industry at Joby Aviation and Rippling, where I built transformer-based models leading to the company’s first [AI product launch](https://www.rippling.com/blog/introducing-talent-signal) featured in Bloomberg.

I am actively seeking opportunities in research and engineering - reach me at zope at stanford dot edu! 

## Updates 

- (Nov, 2025) The WORKBank database has 340+ monthly downloads! We instantiate a novel framework for measuring human-AI collaboration potential and misalignment. Check it out [here](https://futureofwork.saltlab.stanford.edu).
- (Sept, 2025) Had a great summer at Microsoft Research as a Research Intern, working on post-training LLMs for optimization modeling! See our paper [here](https://www.arxiv.org/abs/2509.22979).
- (June, 2025) Co-presented at Stanford NLP Group on Future of Work with AI Agents.
- (March, 2024) Honored to co-host the annual Faculty Dinner for [Stanford Women in Computer Science](https://stanfordwomenincomputerscience.com)!

## Projects

<p><em>*:Equal Contribution</em></p>

<!-- Project 1 -->
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 50px;">

  <!-- Left: Image -->
  <div style="flex: 0 0 150px; text-align: center;">
    <img src="https://raw.githubusercontent.com/hzope6/hzope6.github.io/main/assets/img/optimization.png" alt="Optimization" style="width:100%; border-radius:12px;">
  </div>

  <!-- Right: Text -->
  <div style="flex: 1;">
    <h4 style="margin-top:0;">OptiMind: Teaching LLMs to Think Like Optimization Experts</h4>
    <p>
      Zeyi Chen*, Xinzhi Zhang*, <strong>Humishka Zope*</strong>, Hugo Barbalho, Konstantina Mellou, Marco Molinaro, Janardhan Kulkarni, Ishai Menache, Sirui Li*
    </p>
    <p>
      <a href="https://www.arxiv.org/abs/2509.22979">Preprint (in submission)</a> · September 2025
    </p>
    <p>
      A self-improving LLM framework that enhances optimization reasoning through post-training and test-time scaling with domain expertise, achieving SoTA performance in optimization modeling.
    </p>
  </div>
</div>

<hr style="margin:40px 0;">


<!-- Project 2 -->
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 50px;">

  <!-- Left: Image -->
  <div style="flex: 0 0 150px; text-align: center;">
    <img src="https://raw.githubusercontent.com/hzope6/hzope6.github.io/main/assets/img/workbank-2.png" alt="WORKBank" style="width:100%; border-radius:12px;">
  </div>

  <!-- Right: Text -->
  <div style="flex: 1;">
    <h4 style="margin-top:0;">Future of Work with AI Agents: Auditing Automation and Augmentation Potential across the U.S. Workforce</h4>
    <p>
      Yijia Shao*, <strong>Humishka Zope*</strong>, Yucheng Jiang, Jiaxin Pei, David Nguyen, Erik Brynjolfsson, Diyi Yang
    </p>
    <p>
      <a href="https://arxiv.org/abs/2506.06576">Preprint (in submission)</a> · <a href="https://futureofwork.saltlab.stanford.edu">Website</a> · <a href="https://huggingface.co/datasets/SALT-NLP/WORKBank">HuggingFace (~300+ monthly downloads)</a> · June 2025
    </p>
    <p>
      Developed a framework to measure human–AI collaboration potential and quantify misalignment between human needs and AI capabilities across occupational tasks in diverse domains. Built the <strong>WORKBank</strong> database to map desire–capability misalignment, define the <em>Human Agency Scale</em>, and identify trends in shifting demand for core human skills.
    </p>
    <p>
      <em>Featured in</em> 
      <a href="https://www.forbes.com/sites/moinroberts-islam/2025/06/30/future-of-work-41-of-ai-startups-build-automation-workers-dont-want/">Forbes</a>,
      <a href="https://hai.stanford.edu/news/what-workers-really-want-from-artificial-intelligence">Stanford HAI Report</a>,
      <a href="https://finance.yahoo.com/news/way-ai-100000880.html">Yahoo Finance</a>.  
    </p>
  </div>
</div>

<hr style="margin:40px 0;">


<!-- Project 3 -->
<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 50px;">

  <!-- Left: Image -->
  <div style="flex: 0 0 150px; text-align: center;">
    <img src="https://raw.githubusercontent.com/hzope6/hzope6.github.io/main/assets/img/talent_signal.png" alt="Talent Signal" style="width:80%; border-radius:12px;">
  </div>

  <!-- Right: Text -->
  <div style="flex: 1;">
    <h4 style="margin-top:0;">Talent Signal: AI-Based Performance Management System</h4>
    <p>
      Developed at <strong>Rippling</strong> as a <strong>Machine Learning Engineering Intern</strong>.
    </p>
    <p>
      <em>Launched publicly as a product in 2024 · <a href=https://www.rippling.com/blog/introducing-talent-signal>Blog Post</a> · <a href="https://www.bloomberg.com/news/articles/2024-09-25/rippling-introduces-ai-based-tool-to-evaluate-employee-performance?embedded-checkout=true">Bloomberg coverage</a></em>
    </p>
    <p>
      An AI-based performance management system leveraging transformer-based classification models to assess employee performance.
    </p>
  </div>
</div>
