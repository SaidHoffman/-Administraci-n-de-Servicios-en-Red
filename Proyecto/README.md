# Laboratorio de redes con GNS3

Este proyecto contiene una topología de GNS3 diseñada para estudiar cómo funcionan de forma conjunta distintos componentes de una red: routers, switches, hosts finales, nodos virtuales y entornos basados en contenedores.

## Qué representa esta topología

La red incluida en este laboratorio está pensada para mostrar un escenario más cercano a una infraestructura real, donde varios dispositivos deben comunicarse entre sí y cooperar para ofrecer conectividad. En la práctica, esto permite experimentar con:

- interconexión entre redes
- encaminamiento entre routers
- transmisión de tráfico a través de switches
- conexión de equipos finales y hosts remotos
- uso de tecnologías virtualizadas para ampliar el laboratorio

## Por qué es útil

Este tipo de laboratorio es interesante porque ayuda a comprender cómo se construyen y prueban redes de forma práctica. No se limita a ver una configuración estática: permite observar el comportamiento de una red cuando distintos elementos interactúan entre sí, lo cual es muy valioso para aprender administración de servicios en red.

## Archivos incluidos

- [project.gns3](project.gns3) — definición de la topología del laboratorio
- [project-files](project-files) — recursos y archivos de soporte del proyecto
- [.gitignore](.gitignore) — exclusiones útiles para no subir artefactos innecesarios

## Requisitos de uso

1. Instalar GNS3.
2. Abrir [project.gns3](project.gns3) desde GNS3.
3. Cargar la imagen de IOS necesaria para los routers Cisco 7200.
4. Iniciar la topología y comenzar a probar la conectividad.

## Nota

El laboratorio requiere recursos adicionales propios del entorno de simulación. La imagen de IOS no se distribuye con este repositorio.
