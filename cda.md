---
title: CDA
---

## CDA

Clinical Document Architecture (CDA) is an XML-based markup standard intended to specify the encoding, structure and semantics of clinical documents for exchange. CDA documents are encoded in XML and can be transmitted in HL7 messages.

### Educational Resources

{% if site.data.cda_training.size > 0 -%}
The following table provides an overview of CDA training opportunities available in Austria:

| Thema    | Kategorie | Anbieter | Anmeldung / Anfrage | Zeitraum |
| -------- | ------- |  ------- | ------- | ------- |
{% for training in site.data.cda_training -%}
| {{ training.thema }} | {{ training.kategorie }} | {{ training.anbieter }} | {% if training.anmeldung.url != "" %}{{ training.anmeldung.text }} [{{ training.anmeldung.url }}]({{ training.anmeldung.url }}){% else %}{{ training.anmeldung.text }}{% endif %} | {{ training.zeitraum }} |
{% endfor -%}
{% else -%}
Information about CDA educational resources in Austria will be available soon.
{% endif -%}

### Contact

For training inquiries, please contact: [training@hl7.at](mailto:training@hl7.at)

### Related Links

{% for link in site.data.cda_links -%}
- [{{ link.title }}]({{ link.url }})
{% endfor %}

