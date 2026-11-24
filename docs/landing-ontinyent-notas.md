# Landing "Programación, diseño web y ecommerce en Ontinyent" — notas de integración

Archivo: `programacion-diseno-web-ecommerce-ontinyent.html` (borrador listo, pendiente de integrar en el repositorio).

## Pendiente al integrar en el repo
- Adaptar cabecera, pie y clases a las del sitio real (parece un export de Webflow con HTML estático).
- Entrada en `sitemap.xml` (hoy https://nux.codes/sitemap.xml devuelve error, hay que crearlo):
  ```xml
  <url><loc>https://nux.codes/programacion-diseno-web-ecommerce-ontinyent.html</loc><lastmod>2026-11-24</lastmod><changefreq>monthly</changefreq><priority>0.9</priority></url>
  ```
- `robots.txt` con `Sitemap: https://nux.codes/sitemap.xml`.
- Interlinking entrante: enlace desde la home (menú o sección de servicios), desde `kit-digital-ontinyent.html` y desde el pie de todas las páginas.

## A confirmar por Jose (no inventado, pero sin verificar)
- Coordenadas GPS exactas del local (puse aproximadas del centro de Ontinyent).
- Teléfono principal para el schema (puse 96 191 12 30; en la web también aparece 626 18 41 44).
- Que el proyecto FRANCES y NEW MOP se describan como "web" y no como tienda.
- ~~Nombre y cargo~~: Jose Antonio Donat Fombuena, Front-end Design and Development (añadido).
- Perfiles reales para `sameAs` (Google Business Profile, LinkedIn, Instagram, Facebook): en la web actual apuntan a "#".
- La web actual tiene bloques con "Lorem ipsum" en el portfolio: conviene limpiarlos, restan confianza.

## Origen de las preguntas del FAQ
Semrush no tenía unidades de API disponibles. Las preguntas salen de búsquedas web reales (resultados y "Preguntas relacionadas" sobre precio de web/tienda online, WooCommerce vs PrestaShop, integración con ERP/Factusol, Kit Digital, ventajas de agencia local). Fuentes consultadas: ionos.com, hostinger.com, godaddy.com, shopify.com/es, kinsta.com/es, stelorder.com, red.es, trustlocal.es, proveedores.com.
