# INTICRUNCH · Cuadro de mando estratégico

Prototipo web independiente para Pollos Inti, adaptado de la guía BSC. Está hecho con HTML, CSS y JavaScript. No requiere instalar Odoo, Node.js ni una base de datos y no se conecta al Odoo de AWS.

## Cómo abrirlo

1. Descomprime `INTICRUNCH_Web_BSC.zip`.
2. Abre la carpeta `INTICRUNCH_Web_BSC` en Visual Studio Code.
3. Abre `index.html` con doble clic para usarlo en el navegador. También puedes instalar la extensión **Live Server**, hacer clic derecho en `index.html` y elegir **Open with Live Server**.
4. Inicia sesión con `admin@inticrunch.demo` y `Inti2026!`.

## Módulos

- Dashboard ejecutivo con resultados y gráficos.
- Mapa estratégico organizado en las cuatro perspectivas BSC.
- Objetivos, indicadores KPI, mediciones e iniciativas con formularios.
- Reportes, exportación CSV/JSON y administración de usuarios de demostración.
- Cambios guardados en el almacenamiento local del navegador.

## Adaptación al negocio

Los ejemplos de objetivos e indicadores cubren rentabilidad, costo de alimentos, ticket promedio, satisfacción, recompra, tiempo de preparación, pedidos correctos, merma, capacitación e higiene. **Las metas, avances y mediciones iniciales son datos ilustrativos, no resultados reales de Pollos Inti.** Actualízalos desde la aplicación con la información validada del negocio.

## Límites

El acceso es simulado y los datos solo existen en el navegador donde se registran. No es un sistema multiusuario ni una autenticación segura; no usar para datos confidenciales o producción. Los gráficos usan Chart.js desde CDN y requieren internet; las pantallas restantes funcionan localmente.
