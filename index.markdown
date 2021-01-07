---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: Ana Wang
---

<div class="home-wrapper">
    <div class="home home-text">
      <div class="about">
          <div class="about-top">Bio</div>
          <div class="about-text">  
            {%- include about.html -%}
          </div>
      </div>
      
{%- include projects.html -%}
{%- include values.html -%}
{%- include services.html -%}

</div>



