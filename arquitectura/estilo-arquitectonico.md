# Enfoque arquitectónico

## Características del enfoque

| Elemento | Descripción aplicada al Marketplace |
|---|---|
| Patrón / enfoque arquitectónico | Clean Architecture (Arquitectura Limpia). |
| Objetivo | Separar responsabilidades y controlar las dependencias hacia el dominio. |
| ¿Qué problema resuelve? | Evita que las reglas del negocio dependan directamente de la interfaz Angular, la base de datos, las API y los servicios de pago. |
| Capas definidas | Dominio, Aplicación, Presentación e Infraestructura. |
| Beneficios | Facilita el mantenimiento, las pruebas unitarias y el cambio de tecnologías sin modificar innecesariamente las reglas del negocio. |

## Diagrama del enfoque arquitectónico

![Clean Architecture del Marketplace](imagenes/arquitectura-general.png)