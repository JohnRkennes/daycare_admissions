---
layout: home
published: true
title: Page title
order: 1
---

{% assign sorted_pages = site.pages | sort:"name" %}
{% for node in sorted_pages %}
  <li><a href="{{node.url}}">{{node.title}}</a></li>
{% endfor %}


![alt text is white cat](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b1/VAN_CAT.png/480px-VAN_CAT.png)



The management of a daycare system is a key responsibility for many municipalities around the world. 
A municipality with an effective daycare system is well positioned to attract young families, which are the lifeblood of a vibrant community. 

One successful community in Denmark, which is renown for its effective management of private and public daycares, 
is the city of Copenhagen. Our guide uses Copenhagen as a launching point to critically evaluate the key design principles 
behind the development of an effective daycare system. 
