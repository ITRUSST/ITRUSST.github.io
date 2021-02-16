---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Home
nav_order: 1
permalink: /
---
![](./media/Background3.png)

# Welcome to FUNdamental
We are an international collective working together towards the safe and effective application of transcranial focused ultrasound for neuromodulation. FUNdamental aims to establish consensus on expert guides, guidelines, and standardization for this neuromodulatory technique.

*This website is a placeholder for a more developed alternative and acts as a launching pad for our organization's effort.*

[Get to know us](./about/){: .btn .btn-purple .mx-auto}

---

### Our organization

We would like to thank our contributors:
*we may list our experts here*

### Our repository contributors

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>


<!--
[I'm an inline-style link](https://www.google.com)

[I'm a relative reference to a repository file](../blob/master/LICENSE)

You can find a link to our full size logo [here](./media/FundamentalLogo1.png). -->
