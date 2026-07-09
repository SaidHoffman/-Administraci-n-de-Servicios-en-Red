# Proyecto de laboratorio de redes con GNS3

Este repositorio contiene un proyecto de GNS3 con una topología de laboratorio para practicar y demostrar conceptos de redes. Incluye el archivo de proyecto de GNS3 y los recursos asociados almacenados en la carpeta de proyecto.

## ¿Qué incluye?

- Archivo principal de GNS3: `project.gns3`
- Carpeta con recursos del proyecto: `project-files/`
- Topología con dispositivos Cisco 7200 y nodos VPCS

## Requisitos

Para abrir y ejecutar este laboratorio necesitas:

- GNS3 instalado
- Una imagen de IOS válida para los routers Cisco 7200
- Un sistema operativo compatible con GNS3

## Estructura del proyecto

```text
Proyecto/
├── project.gns3
├── project-files/
│   ├── captures/
│   ├── dynamips/
│   ├── vmware/
│   └── vpcs/
└── README.md
```

## Instrucciones de uso

1. Instala GNS3 en tu equipo.
2. Abre el archivo `project.gns3` desde GNS3.
3. Asegúrate de tener cargada la imagen de IOS correspondiente para los routers.
4. Inicia la topología y configura los equipos según sea necesario.

## Nota importante

El archivo de imagen IOS que usa este laboratorio es un recurso de software propietario y no se incluye en este repositorio. Debes tenerlo disponible localmente para poder ejecutar la topología.

## Autor

Este proyecto fue creado originalmente como un laboratorio de redes y se ha preparado para su publicación en GitHub.
