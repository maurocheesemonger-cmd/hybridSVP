# HybridSVP

Evento deportivo, familiar, inclusivo y solidario del **Colegio San Vicente de Paúl de Alcoy**: tramos de carrera combinados con estaciones físicas adaptadas, desde Infantil hasta adultos.

- **Primera edición (provisional):** sábado 25 de septiembre de 2027 (alternativa: 2 de octubre de 2027).
- **Aforo inicial:** 150–200 participantes, con diseño escalable.
- **Beneficiario previsto:** Capitán Pulmón (pendiente de confirmación).
- **Estado:** fase de definición y planificación.

HybridSVP es un formato propio: no copia HYROX ni es un triatlón. Es un proyecto **independiente** de Club Deportivo SVP y de Coro SVP.

## Contenido del repositorio

| Archivo | Qué es |
|---|---|
| [`docs/INFORMACION.md`](docs/INFORMACION.md) | **Información**: recopilación completa del proyecto (planteamiento, análisis inicial, decisiones con estados DECIDIDO / PENDIENTE / POR VALIDAR, tensiones y próximos pasos). |
| `index.html`, `styles.css` | Web informativa estática del evento. No incluye formularios, pagos ni datos personales. |
| `.nojekyll` | Indica a GitHub Pages que sirva los archivos tal cual. |

## Publicar la web en GitHub Pages

1. En GitHub, abre el repositorio → **Settings** → **Pages**.
2. En **Build and deployment → Source**, elige **Deploy from a branch**.
3. Selecciona la rama que contiene la web y la carpeta **`/ (root)`**, y pulsa **Save**.
4. Al cabo de uno o dos minutos la web estará en `https://<usuario>.github.io/hybridSVP/`.

> GitHub Pages en repositorios privados requiere un plan de pago; en repositorios públicos es gratuito.

## Ver la web en local

Abre `index.html` en el navegador, o ejecuta `python3 -m http.server` en la raíz y visita `http://localhost:8000`.
