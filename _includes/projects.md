{% for link in site.data.publications.main %}

{% if link.image %}   {% endif %} {% if link.conference_short %} {{ link.conference_short }} {% endif %}
{{ link.title }}
{{ link.authors }}
{{ link.conference }}
{% if link.pdf %} PDF {% endif %} {% if link.code %} Code {% endif %} {% if link.page %} Project Page {% endif %} {% if link.bibtex %} BibTex {% endif %} {% if link.notes %} {{ link.notes }} {% endif %} {% if link.others %} {{ link.others }} {% endif %}

{% endfor %}
