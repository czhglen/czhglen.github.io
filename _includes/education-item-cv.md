* **{{degree.title}}**, {{degree.start_date}} -- {% if degree.end_date %} {{degree.end_date}} {% else %} present {% endif %}  
{% if degree.discipline %}{{degree.discipline}}{% endif %}{% if degree.topic %} *{{degree.topic}}*{% endif %}  {% if degree.advisor %}
Advisor: {{degree.advisor}}  {% endif %}
*{{degree.institution}}*, {{degree.location}}
