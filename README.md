# Proyecto-MiShodan

RESUMEN

Siempre que una empresa contrata a un auditor en su plantilla con el objetivo de mantener sus sistemas tanto externos como internos seguros, el auditor solicitara una relación de activos y su criticidad para la empresa, así como la infraestructura de red en donde aparezcan todos los sistemas, ya sean servicios web, bases de datos, sistemas de seguridad, etc.

El problema empieza cuando la empresa no sabe dar respuesta a esa pregunta, ya que a partir de ahí el auditor tendrá que encontrarlos, principalmente entrevistando a los distintos miembros de la empresa. Esta tarea puede llegar a ser un ejercicio sencillo, arduo o extenuante dependiendo de la empresa en donde se desarrolle la actividad.

Pero, si a ese enfoque se le añade una labor de caja negra de localización de direcciones IP activas dentro de la empresa, teniendo en cuenta que cada IP se corresponde con un activo de la empresa, el tiempo de investigación se reduciría.

En la búsqueda de esas IPs, el auditor empezarán sus pesquisas desde el equipo que se le haya asignado dentro de la empresa mirando la IP de su equipo y las IPs de los servidores DNS para hacerse una idea del los rangos de IPs manejados por la empresa. A partir de ahí, empezará a trabajar con distintas herramientas para el descubrimiento de activos, una de esas herramientas puede ser la archiconocida: nmap.

Sin embargo esa tarea necesita un tiempo que el auditor puede no tener debido a la cantidad de entrevistas a realizar.

Por dicho motivo, sería necesario automatizar dicho proceso, lo que implicaría una reducción del tiempo de investigación que el auditor emplearía. 

Ese proceso de automatización es lo que se describe en este documento que está usted leyendo.

Espero que sea de su agrado.

OVERVIEW

When one company hires a auditor inside its staff with the objective to keep theirs computer systems such internal as external safe, the auditor asks for the assets relationship and their criticality for the company, just like the network structure where every systems are, such as web service, data base, security system, etc.

The problem starts when the company doesn’t know to response that question, since there the auditor will have to find it mainly interviewing all of the members of the staff. This task could became a easy,a difficult or exhausting task, depending the company where the auditor is.

But if to the previous point of view we adds a black box task of localization the IP directions inside the company, considering that each IP is a asset of the company, the investigation time will be less

For the search of those IPs, the auditor will start her/his search from the computer inside the company, seeing her/his IP and the IPs of the DNS servers. With these data the auditor could know the ranges of IPs of the company. From there, the auditor will start to work with several tools for descovering the assets, one of these tools can be: nmap

However, that task needs a time what the auditor couldn’t have due to the number of interviews to be conducted

That’s why, it will be neccesary to automative this task, this will get to have less time of investigation by auditor

That task of automation is described in this document.

I hope it’s to your liking
