<!--Import Google Icon Font-->
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
<!--Import materialize.css-->
<link type="text/css" rel="stylesheet" href="css/materialize.min.css"  media="screen,projection"/>

<!--Let browser know website is optimized for mobile-->
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

## Intro

The language learning process require continuous learning. At least 15 minutes per day. 
The brain is kept posted then and improve quickly in the new language we're learning.

## Our deal

One english topic per day is a good deal.

## Links

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% for post in site.posts %}

{{ post }}

{{ post.author}} {{ post.date }}

{% endfor %}

<div class="red-text">OK</div>
