# Release 0.1.0

**Fecha:** 2026-06-23

## Resumen

Primera base trazable del proyecto `cremheda.online`.
Esta entrega deja documentada la landing page inicial y establece una referencia para futuros cambios.

## Alcance de esta entrega

- una pagina principal en `index.html`
- estructura comercial completa para presentar el servicio
- calculadora de presupuesto interactiva
- formulario de contacto con modal de confirmacion
- navegacion responsive para escritorio y movil
- contenido base para marca, servicios y cierre comercial

## Cambios relevantes

- Se definio la propuesta de valor de Cremheda como servicio cercano para negocios locales.
- Se incorporo una seccion de comparativa frente a proveedores grandes.
- Se agrego una calculadora para estimar el precio mensual.
- Se incluyo un formulario de contacto con experiencia de exito.
- Se reforzo el look and feel con Tailwind y tipografias externas.

## Dependencias conocidas

- Tailwind CSS via CDN
- Google Fonts via CDN
- JavaScript embebido en la misma pagina

## Observaciones

- El formulario no envia datos a un backend real; la experiencia actual es solo visual.
- El contenido incluye datos de ejemplo que deben revisarse antes de publicar en produccion.
- La pagina depende de conexion a internet para cargar fuentes y estilos externos.

## Riesgos abiertos

- Falta persistencia real de los mensajes del formulario.
- No existe versionado automatizado de releases.
- No hay pruebas automatizadas.

## Proximos hitos sugeridos

1. Integrar un backend o servicio de formularios.
2. Externalizar CSS y JavaScript.
3. Crear version 0.2.0 con datos reales y textos finales.
4. Definir un flujo formal de revision y aprobacion de cambios.
