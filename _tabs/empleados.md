---
layout: page
title: Equipo
order: 5
---

**Nuestro Equipo**

<table>
 <tr>
   <th>Nombre</th> 
   <th>Cargo</th> 
   <th>Departamento</th> 
</tr> 
{% for empleado in site.data.empleados %}
    <tr> <td>{{ empleado.nombre }} </td> 
    <td> {{ empleado.cargo }} </td>
    <td>{{ empleado.departamento }} </td>
    </tr>
{% endfor %}
