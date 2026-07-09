# Proyecto de gestión de red con Python y GNS3

Este proyecto está basado en un requisito de desarrollo para crear una API REST en Python que permita gestionar una red de cómputo de forma segura y automatizada. Como parte del laboratorio, se utiliza una topología simulada en GNS3 para representar la red sobre la que debe operar la API.

## Objetivo del proyecto

Desarrollar una solución que permita:

- comunicarse con dispositivos de red de forma segura mediante SSH
- gestionar usuarios de red y permisos de acceso
- consultar información de routers e interfaces
- detectar la topología de la red de forma dinámica
- generar una representación gráfica de la topología
- responder con códigos HTTP apropiados, como 404 cuando un elemento no existe

## Qué hace la solución

La API debería exponer operaciones para:

- gestionar usuarios globales y por router mediante CRUD
- consultar la información general de los routers de la red
- consultar información por interfaz de cada router
- detectar y actualizar la topología de la red
- generar una gráfica de la topología existente

## Qué representa esta topología

La topología incluida en este proyecto simula una infraestructura de red con routers, switches, hosts y recursos virtualizados que sirven como entorno de prueba para validar el comportamiento del sistema. Incluye dispositivos como routers Cisco, switches y equipos finales, lo que permite trabajar con un escenario más cercano a una red real.

## Valor del proyecto

Este tipo de proyecto es interesante porque une tres áreas muy importantes:

- redes y administración de infraestructura
- automatización con Python
- diseño de servicios web mediante API REST

Es una muestra clara de cómo se puede combinar la teoría de redes con herramientas modernas de desarrollo para construir soluciones prácticas y escalables.

## Archivos incluidos

- [project.gns3](project.gns3) — definición principal de la topología utilizada para la prueba del sistema
- [project-files](project-files) — recursos y archivos de apoyo del laboratorio
- [.gitignore](.gitignore) — exclusiones para mantener el proyecto más limpio

## Requisitos para usarlo

1. Instalar GNS3.
2. Abrir [project.gns3](project.gns3).
3. Cargar la imagen de IOS necesaria para los routers Cisco 7200.
4. Ejecutar la solución de gestión de red sobre la topología simulada.

## Nota

La imagen de IOS no se incluye en este repositorio; debe estar disponible localmente para ejecutar la topología correctamente.
