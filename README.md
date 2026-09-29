# Conexion2026

Front-End JS

## Talento Lab

En esta práctica se desarrolló una página de contacto utilizando
formularios y tablas en HTML.

## Formulario de contacto

Se creó un formulario que permite ingresar:

- Nombre
- Correo electrónico
- Asunto
- Mensaje

Los campos utilizan etiquetas `label` e `input`, junto con atributos
como `required` para realizar validaciones básicas desde el navegador.

## Configuración de Formspree

Para permitir el envío de los datos del formulario se utilizó Formspree.

Se creó un formulario en la plataforma y se agregó la URL proporcionada
por Formspree al atributo `action` del formulario HTML.

También se utilizó el método `POST` para realizar el envío de los datos.

Ejemplo:

```html
<form action="URL-PROPORCIONADA-POR-FORMSPREE" method="POST">
