---
title: DICOM
---

## DICOM

Digital Imaging and Communications in Medicine (DICOM) is the international standard for medical images and related information. It defines the formats for medical images that can be exchanged with the data and quality necessary for clinical use.

### Educational Resources

{% if site.data.dicom_training.size > 0 -%}
The following table provides an overview of DICOM training opportunities available in Austria:

| Thema    | Kategorie | Anbieter | Anmeldung / Anfrage | Zeitraum |
| -------- | ------- |  ------- | ------- | ------- |
{% for training in site.data.dicom_training -%}
| {{ training.thema }} | {{ training.kategorie }} | {{ training.anbieter }} | {% if training.anmeldung.url != "" %}{{ training.anmeldung.text }} [{{ training.anmeldung.url }}]({{ training.anmeldung.url }}){% else %}{{ training.anmeldung.text }}{% endif %} | {{ training.zeitraum }} |
{% endfor -%}
{% else -%}
Information about DICOM educational resources in Austria will be available soon.
{% endif -%}

### Contact

For training inquiries, please contact: [training@hl7.at](mailto:training@hl7.at)

### Related Links

{% for link in site.data.dicom_links -%}
- [{{ link.title }}]({{ link.url }})
{% endfor %}

