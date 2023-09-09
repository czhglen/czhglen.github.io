* **{{degree.title}}** in ***{{degree.discipline}}***, **{{degree.start_date}}** -- {% if degree.end_date %} **{{degree.end_date}}** {% else %} present {% endif %}   
{{degree.institution}}, {{degree.location}}  {% if degree.topic %} 
Thesis: {{degree.topic}}{% endif %}  {% if degree.advisor %}
Supervisor(s): {{degree.advisor}}  {% endif %}
