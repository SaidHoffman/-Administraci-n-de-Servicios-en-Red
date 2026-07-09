# Administración de Servicios en Red

Este repositorio contiene un laboratorio de red reproducible creado en GNS3. La topología simula una infraestructura de red más realista de lo que suele verse en un ejercicio básico: combina routers Cisco, switches, equipos finales, hosts virtualizados y servicios en contenedores para mostrar cómo se interconectan diferentes capas de una red.

## ¿Qué hace este proyecto?

La topología permite practicar y demostrar conceptos fundamentales de redes, como:

- enrutamiento entre redes
- conmutación y segmentación de tráfico
- comunicación entre equipos finales
- integración de dispositivos virtuales y contenedores
- prueba de conectividad y comportamiento de una red pequeña pero funcional

## ¿Por qué es interesante?

Este laboratorio no es solo un dibujo de red: es una herramienta práctica para entender cómo se construyen, prueban y operan entornos de red reales. Lo hace más valioso porque mezcla tecnologías tradicionales de red con entornos modernos de virtualización, lo que ayuda a conectar la teoría con escenarios más cercanos a la práctica profesional.

## Estructura del repositorio

- [Proyecto](Proyecto) — carpeta principal con el proyecto GNS3 y los archivos asociados
- [Proyecto/README.md](Proyecto/README.md) — descripción adicional del laboratorio

## Requisitos

Para abrir y ejecutar la topología se necesita:

- GNS3 instalado
- una imagen de IOS válida para los routers Cisco 7200
- el entorno compatible con las máquinas virtuales o contenedores incluidos en la topología

## Nota importante

La imagen de IOS no se incluye en este repositorio. Debe estar disponible localmente para poder iniciar la topología correctamente.
