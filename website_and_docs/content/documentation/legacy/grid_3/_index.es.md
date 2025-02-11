---
title: "Grid 3"
linkTitle: "Grid 3"
weight: 6
aliases: ["/documentation/es/grid/grid_3/"]
---

{{% pageinfo color="warning" %}}
<p class="lead">
   <i class="fas fa-language display-4"></i> 
   Most of the documentation found in this section is still in English.
   Please note we are not accepting pull requests to translate this content
   as translating documentation of legacy components does not add value to
   the community nor the project.
</p>
{{% /pageinfo %}}

_Selenium Grid_ es un servidor inteligente que efectúa de proxy que permite a los
tests de Selenium enrutar sus comandos hacia instancias remotas de navegadores
web.
La intención de esto es proporcionar una forma sencilla de ejecutar los tests en
paralelo en múltiple maquinas.


Con _Selenium Grid_ un servidor actúa como el centro de actividad (_hub_) 
encargado de enrutar los comandos de los tests en formato JSON hacia uno o mas
nodos registrados en el _Grid_.
Los tests contactan con el hub para obtener acceso a las instancias remotas de
los navegadores.

_Selenium Grid_ te permite ejecutar los tests en paralelo en múltiples maquinas
y también te permite gestionar diferentes versiones de navegadores y diferentes
configuraciones de navegadores de manera centralizada (en lugar de hacerlo de
manera individual en cada test)

_Selenium Grid_ no es una solución mágica para todos tus problemas.
Permite resolver un subconjunto de problemas comunes de delegación y distribución,
pero, por ejemplo, no administrará su infraestructura y podría no satisfacer sus
necesidades personales.
