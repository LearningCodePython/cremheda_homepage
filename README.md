# Cremheda Homepage

Landing page de presentacion para `cremheda.online`, orientada a digitalizar negocios locales con una propuesta cercana y simple.

## Proposito

Este proyecto arranca como una pagina web unica que comunica la propuesta de valor de Cremheda:

- creacion de web para negocios locales
- configuracion de correo profesional
- gestion de dominio, SSL y hosting
- soporte tecnico y mantenimiento
- calculadora de precio mensual
- formulario de contacto con modal de confirmacion

## Estado del proyecto

- Implementacion actual: `index.html`
- Tipo de proyecto: landing page estatica autocontenida
- Estilo visual: Tailwind CSS via CDN
- Tipografia: Google Fonts (`Plus Jakarta Sans` y `Outfit`)
- Idioma principal: espanol

## Funcionalidades actuales

- Navegacion fija con menu desktop y menu mobile
- Hero con mensaje principal y llamadas a la accion
- Seccion comparativa de diferencial frente a grandes proveedores
- Seccion de servicios
- Flujo de trabajo en 3 pasos
- Calculadora interactiva de presupuesto
- Formulario de contacto con modal de exito
- Footer con datos de contacto y enlaces legales

## Estructura

- `index.html`: pagina principal y toda la logica frontend
- `README.md`: guia base del proyecto y trazabilidad
- `release.md`: historial inicial de entrega y cambios

## Lógica de la pagina

La interaccion esta implementada con JavaScript embebido en el propio `index.html`:

- control del menu mobile
- seleccion del tipo de web
- actualizacion del numero de cuentas de correo
- calculo del precio mensual estimado
- envio simulado del formulario y apertura del modal de exito

## Dependencias externas

El proyecto depende de servicios CDN y fuentes externas:

- Tailwind CSS via `https://cdn.tailwindcss.com`
- Google Fonts via `fonts.googleapis.com` y `fonts.gstatic.com`

## Datos y contenido

La pagina incluye contenido comercial de ejemplo, incluyendo:

- nombre de negocio de muestra
- correo de ejemplo
- dominio de ejemplo
- direccion de oficina de ejemplo

Si este contenido se va a publicar, conviene revisar y sustituir los datos de demostracion por informaciones reales.

## Como usarlo

1. Abre `index.html` en un navegador.
2. Comprueba la visualizacion en escritorio y movil.
3. Ajusta textos, precios y datos de contacto segun el negocio real.
4. Si se desea publicar, alojar el archivo en un servidor web estatico.

## Criterios de trazabilidad inicial

Para poder seguir la evolucion del proyecto, conviene registrar en cada cambio:

- fecha
- archivo modificado
- motivo del cambio
- impacto funcional
- estado de verificacion

## Siguientes pasos recomendados

1. Separar estilos y scripts en archivos propios si el proyecto crece.
2. Añadir una politica de privacidad y aviso legal reales.
3. Sustituir el envio simulado del formulario por una integracion real.
4. Crear un sistema de versionado semantico para futuras entregas.
