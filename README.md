# JC Collectibles

Aplicación web para administrar cartas deportivas, registrar costos y valores estimados y organizar inventario.

## Ejecutar localmente

1. Instala Node.js 20 o superior.
2. Descarga o clona este repositorio.
3. Abre una terminal en la carpeta del proyecto.
4. Ejecuta `npm install`.
5. Ejecuta `npm run dev`.
6. Abre la dirección local que muestre Vite (normalmente http://localhost:5173).

## Funciones actuales

- Crear y eliminar cartas.
- Buscar cartas en el inventario.
- Clasificar en Collection, For Sale, Sold, Grading y Wishlist.
- Registrar costo y valor estimado manualmente.
- Exportar CSV.
- Abrir búsqueda externa en SportsCardsPro para cada carta.

## Limitaciones importantes

- Los datos se guardan en localStorage del navegador: no están sincronizados entre equipos. Exporta CSV como respaldo.
- Los precios no se importan automáticamente desde SportsCardsPro. Se requiere confirmar acceso autorizado a datos o API y diseñar un proceso de matching confiable.
- No hay cuentas, imágenes ni base de datos en la nube todavía.
