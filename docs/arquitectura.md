---
layout: default
title: Arquitectura
---

# Arquitectura del Proyecto

En esta sección se presenta la estructura inicial del proyecto y la organización de archivos prevista. La imagen muestra la disposición de carpetas dentro del entorno de desarrollo, incluyendo configuraciones relacionadas con Docker, Composer y otros elementos necesarios para la futura implementación.

---

## Estructura del proyecto

![Estructura del proyecto](img/arquitectura.png)

La estructura mostrada refleja una organización pensada para:

- Separar claramente la documentación del código.
- Mantener configuraciones de Docker y Composer accesibles.
- Facilitar la escalabilidad del proyecto.
- Preparar el entorno para integrar bases de datos, autenticación y minijuegos.

---

## Tecnologías previstas

A continuación se muestra una tabla comparativa de las tecnologías que se utilizarán en el desarrollo del proyecto y su función dentro del sistema.

| Tecnología | Uso previsto | Ventajas | Motivo de elección |
|-----------|--------------|----------|---------------------|
| **Firebase** | Autenticación, almacenamiento en tiempo real | Fácil integración, escalabilidad | Ideal para gestionar usuarios y datos dinámicos |
| **MySQL** | Base de datos estructurada | Estándar, robusta, ampliamente soportada | Perfecta para almacenar información persistente y relacional |
| **Godot** | Desarrollo de minijuegos | Ligero, exportación web, open source | Permite añadir elementos interactivos dentro de la plataforma |
| **Docker** | Contenedores y entorno reproducible | Aísla servicios, facilita despliegues | Garantiza que el entorno sea estable y replicable |
| **Composer** | Gestión de dependencias PHP (si aplica) | Automatiza librerías y versiones | Útil si se integra backend en PHP |
| **GitHub Pages** | Despliegue de la documentación | Simple, gratuito, integrado con GitHub | Ideal para publicar la documentación del TFG |
| **Jekyll + Markdown** | Generación de la documentación | Sencillo, limpio, mantenible | Facilita la creación de documentación clara y estructurada |

---

[⬅️ Volver al inicio](index.md)