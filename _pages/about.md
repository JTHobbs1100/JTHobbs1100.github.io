---
permalink: /
# title: <h1 style="font-family:'Courier New'">Hello, world! </h1>
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

> "...a decidedly queer approach can question the very logics of visibility with which algorithmic systems and AI are trained." 
> --- <a href="https://www.taylorfrancis.com/chapters/oa-edit/10.4324/9781003357957-1/introduction-michael-klipphahn-karge-ann-kathrin-koster-sara-morais-dos-santos-bruss" style="font-style: normal;"> Klipphahn-Karge et al. </a>

My name is Jacob Hobbs! I'm currently working as a Software Engineer for <a href="https://www.costargroup.com/">CoStar Group</a> in Arlington, VA just outside of Washington, DC. I graduated with High Distinction from the University of Virginia in 2025 (<a href="https://doi.org/10.18130/f4gz-t155">read my thesis on <i>Theories of 'Sexuality' in NLP Bias Research</i></a>). Outside of work, I'm a visiting researcher at Carnegie Mellon University and work heavily with <a href="https://www.queerinai.com/">Queer in AI</a>. I'm currently working on a couple independent and group research projects related to queerness and bias evaluations in NLP! 

## Research Interests
My current research interests can be categorized into broad fields of Natural Language Processing and the societal implications of artificial intelligence systems with a specific focus on how LGBTQIA+ identities impact/are impacted by these systems. My research goal is to develop new methods of measuring & mitigating biases in LLMs while using social science & participatory methods to inform a more fair and equitable AI future. 

## Publications {#publications}

{% for post in site.publications reversed %}
  {% unless forloop.first %}
<div style="margin-bottom: 1.5em;"></div>
  {% endunless %}
  {% include archive-single.html %}
{% endfor %}

## Teaching {#teaching}

{% for post in site.teaching reversed %}
  {% unless forloop.first %}
<div style="margin-bottom: 1em;"></div>
  {% endunless %}
  {% include archive-single.html %}
{% endfor %}

## Press {#press}

{% for post in site.press reversed %}
  {% unless forloop.first %}
<div style="margin-bottom: 1em;"></div>
  {% endunless %}
  {% include archive-single.html %}
{% endfor %}