# Titulo: Template de documento de diseño
---
## Overview: Problema a resolver
Descripción..

### Alcance(Scope)
Descripción..

#### Casos de uso
Descripción...
* Caso de uso 1
* Caso de uso 2
* ...

#### Out of Scope (casos de uso No Soportados)
Descripción...
* Caso de uso 1
* Caso de uso 2
* ...
---
## Arquitectura

### Diagramas
poner diagramas de secuencia, uml, etc

### Modelo de datos
Poner diseño de entidades, Jsons, tablas, diagramas entidad relación, etc..

---

### Plan de pruebas (opcional)
definir las pruebas de las funcionalidades
Ej.
crear usuario, editar usuario, ver reportes

### Integracion continua (opcional)
puede tener diagramas de como va a ser la distribucion del sistema
Ej.
* Ambiente de desarrollo
* Ambiente de testing
* Ambiente de produccion

 De desarrollo se envia a testing, si pasa las pruebas se envia a producción

## Limitaciones
Lista de limitaciones conocidas. Puede ser en formato de lista.
Ej.
* Llamadas del API tienen latencia X
* No se soporta mas de X llamadas por segundo
---
## Costo (opcional)
Descripción/Análisis de costos
Ejemplo:
"Considerando N usuarios diarios, M llamadas a X servicio/baseDatos/etc"
* 1000 llamadas diarias a serverless functions. $XX.XX
* 1000 read/write units diarias a X Database on-demand. $XX.XX
Total: $xx.xx (al mes/dia/año)
