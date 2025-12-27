---
title: FHIR
---

## FHIR

Fast Healthcare Interoperability Resources (FHIR) is a next generation standards framework created by HL7. FHIR combines the best features of HL7's v2, HL7 v3 and CDA product lines while leveraging the latest web standards and applying a tight focus on implementability.

### Training and Educational Opportunities in Austria

The following table provides an overview of FHIR training opportunities available in Austria:

| Thema    | Kategorie | Anbieter | Anmeldung / Anfrage | Zeitraum |
| -------- | ------- |  ------- | ------- | ------- |
{% for training in site.data.fhir_training -%}
| {{ training.thema }} | {{ training.kategorie }} | {{ training.anbieter }} | {% if training.anmeldung.url != "" %}{{ training.anmeldung.text }} [{{ training.anmeldung.url }}]({{ training.anmeldung.url }}){% else %}{{ training.anmeldung.text }}{% endif %} | {{ training.zeitraum }} |
{% endfor %}

### Contact

For training inquiries, please contact: [training@hl7.at](mailto:training@hl7.at)

### Related Links

{% for link in site.data.fhir_links -%}
- [{{ link.title }}]({{ link.url }})
{% endfor %}

