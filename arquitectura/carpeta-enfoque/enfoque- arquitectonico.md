Dentro de la carpeta arquitectura, crear una sub carpeta enfoque y dentro crear el archivo enfoque-arquitectonico.md
Las dependencias internas mediante Clean Architecture.

| Elemento | Descripción aplicada al Marketplace |
| :--- | :--- |
| Patrón / enfoque arquitectónico | Clean Architecture (Arquitectura Limpia). |
| Objetivo | Separar responsabilidades y controlar las dependencias hacia el dominio. |
| ¿Qué problema resuelve? | Evita el acoplamiento entre la interfaz Angular, las reglas del negocio y las tecnologías externas, como bases de datos, API y servicios de pago. |
| Capas definidas | Presentación, Aplicación, Dominio e Infraestructura. |
| Beneficios | • Facilita el mantenimiento y las pruebas unitarias.<br>• Permite cambiar implementaciones técnicas sin modificar innecesariamente las reglas del negocio.<br>• Mejora la organización y separación de responsabilidades del código. |

(imagen del diagrama)
![Patron arquitectonico](imagenes/patron-arquitectonico.png)