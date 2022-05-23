<nav>
<a href="index.html"> Home   | </a>
<a href="Steps.html"> Steps  |</a>
<a href="testimonial.html"> Testimonial for TWT </a>
</nav>

# Passenger List

This page includes the name and Age of the passengers travelling in Titanic:

{% for item in site.data.titanic %}
-  {{item.Name}}, {{item.Age}}
{% endfor %}
