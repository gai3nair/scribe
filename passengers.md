<nav>
<a href="index.html"> Home   | </a>
<a href="Steps.html"> Steps  |</a>
<a href="testimonial.html"> Testimonial for TWT </a>
</nav>

# Passenger List

This page includes the following information about the passengers travelling in Titanic:

{% for item in site.data.titanic %}
- **Name:** {{item.Name}} - **Age:** {{item.Age}}
{% endfor %}
