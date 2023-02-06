---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Bernhard Stadlbauer
description: Bernhard Stadlbauer is a senior data engineer at Pachama based in Graz, Austria.
---

<div class="space-y-xl">
  <div class="space-y-md">
    <h1>Hi, I'm Bernhard!</h1>
    <p>
      I build virtual systems to plant real trees 🌳 at <a href="https://www.pachama.com" target="_blank" class="inline">Pachama</a>. On and off work I believe in the power of open source software and sharing what I've learned with the community.
    </p>
  </div>
  <div class="link-bar space-x-md">
    {% for link in site.data.socialLinks %}
    <a target="_blank" href="{{link.url}}" class="space-x-sm"><img class="social-icon" src="{{link.iconPath}}"><span>{{link.name}}</span></a>
    {% endfor %}
  </div>

</div>
