---
layout              : page-fullwidth
show_meta           : false
title               : "PYNQ Boards"
subheadline         : 
teaser              : 
header:
   image_fullwidth  : "White.png"
permalink           : "/boards/"
---

See our collection of PYNQ boards!

<div class="row">
{% for item in site.data.boards.docs limit:2 %}
<div class="column">
  <div class="card" padding-bottom="20px">
    <img class="cardimg" src="{{ site.urlimg }}{{ item.img }}" class="img-fluid" alt="{{ item.board }}">
    <h1>{{ item.board }}</h1>
    <p class="price">{{ item.subhead }}</p>
    <p>{{ item.info }}</p>
    <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
  </div>
</div>
{% endfor %}
</div>

<div class="row">
{% for item in site.data.boards.docs offest:2 limit:1 %}
<div class="column">
  <div class="card" padding-bottom="20px">
    <img class="cardimg" src="{{ site.urlimg }}{{ item.img }}" class="img-fluid" alt="{{ item.board }}">
    <h1>{{ item.board }}</h1>
    <p class="price">{{ item.subhead }}</p>
    <p>{{ item.info }}</p>
    <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
  </div>
</div>
{% endfor %}
</div>

<h2>Xilinx boards with PYNQ compatibility</h2>

<div class="row">
{% for item in site.data.boards.docs offset:3 limit:4 %}
<div class="column">
  <div class="card" padding-bottom="20px">
    <img class="cardimg" src="{{ site.urlimg }}{{ item.img }}" class="img-fluid" alt="{{ item.board }}">
    <h1>{{ item.board }}</h1>
    <p class="price">{{ item.subhead }}</p>
    <p>{{ item.info }}</p>
    <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
  </div>
</div>
{% endfor %}
</div>

<h2>Other PYNQ compatible boards</h2>

<div class="row">
{% for item in site.data.boards.docs offset:7 limit:2 %}
<div class="column">
  <div class="card" padding-bottom="20px">
    <img class="cardimg" src="{{ site.urlimg }}{{ item.img }}" class="img-fluid" alt="{{ item.board }}">
    <h1>{{ item.board }}</h1>
    <p class="price">{{ item.subhead }}</p>
    <p>{{ item.info }}</p>
    <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
  </div>
</div>
{% endfor %}
</div>

<div class="row">
{% for item in site.data.boards.docs offset:9 limit:1 %}
<div class="column">
  <div class="card" padding-bottom="20px">
    <img class="cardimg" src="{{ site.urlimg }}{{ item.img }}" class="img-fluid" alt="{{ item.board }}">
    <h1>{{ item.board }}</h1>
    <p class="price">{{ item.subhead }}</p>
    <p>{{ item.info }}</p>
    <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
  </div>
</div>
{% endfor %}
</div>

