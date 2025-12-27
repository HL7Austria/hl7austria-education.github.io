---
title: SNOMED CT
---

## SNOMED CT

SNOMED CT (Systematized Nomenclature of Medicine - Clinical Terms) is a comprehensive clinical terminology that provides a standardized way to represent clinical information across the continuum of care. It is the most comprehensive multilingual clinical healthcare terminology in the world.

### Educational Resources

{% if site.data.snomed_training.size > 0 -%}
The following table provides an overview of SNOMED CT training opportunities available in Austria:

| Thema    | Kategorie | Anbieter | Anmeldung / Anfrage | Zeitraum |
| -------- | ------- |  ------- | ------- | ------- |
{% for training in site.data.snomed_training -%}
| {{ training.thema }} | {{ training.kategorie }} | {{ training.anbieter }} | {% if training.anmeldung.url != "" %}{{ training.anmeldung.text }} [{{ training.anmeldung.url }}]({{ training.anmeldung.url }}){% else %}{{ training.anmeldung.text }}{% endif %} | {{ training.zeitraum }} |
{% endfor -%}
{% else -%}
Information about SNOMED CT educational resources in Austria will be available soon.
{% endif -%}

### Contact

For training inquiries, please contact: [training@hl7.at](mailto:training@hl7.at)

### Related Links

{% for link in site.data.snomed_links -%}
- [{{ link.title }}]({{ link.url }})
{% endfor %}

