---
title: Advisory Board
---

The Scientific Advisory Board acts as a consulting body to the Consortium Management Group and the Consortium overall.  The board members are sought to represent a variety of international health and policy organisations as well as research institutions with a breadth of experience relevant to the Consortium key objectives. The board members were nominated during the first year of the Consortium operations for a five year term.    

Scientific Advisory Board members:

<div id="advisory-board-list">
  {% for person in site.data.advisory-board %}
    {% if person.url %}
	  <a href="{{ person.url }}">
        <strong>{{ person.name }}</strong>
	  </a>
	{% else %}
	  <strong>{{ person.name }}</strong>
	{% endif %}
	
	{% if person.title %}
	  <br/>
	  {{ person.title }}
	{% endif %}
	<br/><br/>
  {% endfor %}
</div>

*Additional members pending*
