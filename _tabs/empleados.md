---
layout: page
title: Equipo
order: 5
---


| Nombre | Posición | Departamento |


{% for empleado in site.data.empleados %}
| {{ empleado.nombre }} | {{ empleado.cargo }} | {{ empleado.departamento }} |
{% endfor %}
{: .table-striped .table-bordered }