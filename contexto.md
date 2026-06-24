# Contexto del proyecto

**Fecha de registro:** 2026-06-24

## Estado actual

El proyecto `cremheda.online` es una landing page estática en un único archivo principal:

- `index.html` contiene la estructura, estilos vía Tailwind CDN y toda la lógica en JavaScript embebido.
- `README.md` documenta la base del proyecto y su trazabilidad inicial.
- `release.md` recoge la release `0.1.0`.

La web ya tiene:

- hero principal con CTA a calculadora y WhatsApp
- secciones de diferencial, servicios, proceso y calculadora
- bloque de contacto “¿Hablamos?”
- footer con datos de marca

## Decisiones ya tomadas

- El botón principal de WhatsApp abre conversación directa con el número `+34 646 19 21 90`.
- La firma del fundador se ha adaptado a `Cristo - Fundador de Cremheda`.
- La sección “La Experiencia Cremheda” enfatiza cercanía, presencia digital básica y coste bajo para comercio local.
- El formulario de “¿Hablamos?” ya no es solo visual: hoy deriva a WhatsApp Web con los datos del usuario redactados automáticamente.

## Objetivo siguiente

Quiero cambiar el formulario de contacto a la **opción 2: envío directo a un correo vuestro mediante backend**.

La idea es que el formulario:

- envíe los datos a un endpoint propio o a un servicio backend
- genere un correo real con la consulta del cliente
- deje de depender de WhatsApp como canal principal de entrada

## Lo que hay que hacer después

1. Elegir la implementación del backend.
2. Definir el correo remitente y el correo receptor.
3. Crear el endpoint de recepción del formulario.
4. Conectar el formulario del frontend con ese endpoint.
5. Mostrar estados claros de éxito y error.
6. Añadir protección básica contra spam.
7. Revisar la experiencia final y actualizar `README.md` y `release.md`.

## Recomendación de trabajo

Para continuar sin perder contexto, conviene revisar primero:

- cómo se va a alojar el sitio
- si habrá backend propio o servicio externo
- qué proveedor de correo se usará para enviar las consultas

## Notas importantes

- No asumir que el formulario actual ya está listo para producción.
- Mantener la web ligera y simple, porque el proyecto está orientado a una presencia básica para pequeños negocios.
- Cualquier cambio futuro debe conservar el tono cercano y comercial del sitio.
