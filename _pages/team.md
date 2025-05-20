---
title: "Huang-TOMC Lab - Team"
layout: gridlay
excerpt: "Huang-TOMC Lab -- Team"
sitemap: false
permalink: /team/
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

# Group Members

**我们正在招收优秀的硕士/博士研究生，以及博士后！** [(see openings)]({{ site.url }}{{ site.baseurl }}/openings) **!**

## Faculty
{% assign number_printed = 0 %}
{% for member in site.data.advisors %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="50%"  />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}
  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

***

## PostDoc Members

{% assign number_printed = 0 %}
{% for member in site.data.postdoc23 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-md-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="50%"  />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">


  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

***

## PhD Students

{% assign number_printed = 0 %}
{% for member in site.data.phd22 %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-md-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="50%" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">


  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 3 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}


***

## MS Students

{% assign number_printed = 0 %}
{% for member in site.data.ms24 %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}

<div class="row">
{% endif %}


<div class="col-md-3 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="50%" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <ul style="overflow: hidden">


  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>

  <div class="social-links"> 
  {% if member.website%} <a href="{{ member.website }}"> <i class="fa fa-link"></i></a> {% endif %}
  {% if member.email%} <a href="mailto:{{ member.email }}"> <i class="fa fa-envelope"></i></a> {% endif %}
  {% if member.scholar%} <a href="{{ member.scholar }}"> <i class="fa fa-google"></i></a> {% endif %}
  {% if member.linkedin%} <a href="{{ member.linkedin }}"> <i class="fa fa-linkedin"></i></a> {% endif %}
  {% if member.github%} <a href="{{ member.github }}"> <i class="fa fa-github"></i></a> {% endif %}
  {% if member.twitter%} <a href="{{ member.twitter }}"> <i class="fa fa-twitter"></i></a> {% endif %} 
  </div>

</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 3 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

***

