---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: home
nav_order: 1
permalink: /
---
![](./media/Background3.png)
![](./media/ITRUSSTLogo7.png)
# Welcome to ITRUSST
**International Transcranial Ultrasonic Stimulation Safety and Standards.** We are an international consortium working together towards the safe and effective application of transcranial focused ultrasound for neuromodulation. ITRUSST aims to establish consensus on expert guides, guidelines, and standardization for this neuromodulatory technique.

[Get to know us](./about/){: .btn .btn-purple .mx-auto}

---

### Our repository contributors

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"/></a>
  </li>
{% endfor %}
</ul>


<!DOCTYPE html>
<meta charset="utf-8">
<title>Redirecting to https://itrusst.com/</title>
<meta http-equiv="refresh" content="0; URL=https://itrusst.com/">
<link rel="canonical" href="https://itrusst.com/">

<!--
[I'm an inline-style link](https://www.google.com)

[I'm a relative reference to a repository file](../blob/master/LICENSE)

You can find a link to our full size logo [here](./media/ITRUSSTLogo1.png). -->
