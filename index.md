---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Bernhard Stadlbauer
description: Bernhard Stadlbauer is a senior data engineer at Pachama based in Graz, Austria.
---

<div class="space-y-xl">
  <div class="space-y-md">
    <h1>Bernhard Stadlbauer</h1>
    <p>
      I am Bernhard. Serial entrepreneur 🚀, python evangelist and
      semi-professional pizza chef 🍕. I build virtual systems to plant real
      trees 🌳 at Pachama and real muscles on fake rocks 🧗‍♂️ in Graz, Austria. I
      regularily present my work to a bunch of vim-nerds at Linux Tage.
    </p>
  </div>
  <div class="link-bar space-x-md">

{% for link in site.data.socialLinks %}
<a target="_blank" href="{{link.url}}" class="space-x-sm"><img class="social-icon" src="{{link.iconPath}}"><span>{{link.name}}</span></a>
{% endfor %}

  </div>

</div>
