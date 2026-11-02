# JC Collectibles

Inventario de cartas en español sin dependencias ni claves API.

## Abrir

Descarga index.html y ábrelo en un navegador moderno. Si IndexedDB está bloqueado en archivos locales, usa un servidor estático local. Card Vault.html contiene la misma app para conservar el nombre anterior.

## Funciones

Fotos frontal y posterior, edición, búsqueda, filtros, compras, ventas, gastos, respaldo JSON con fotos, importación por identificador y exportación CSV. Enlaces de comparación en eBay y anuncios preparados con tus datos.

Ganancia neta = venta - compra - gastos; incluye solo ventas con los tres importes completos.

## Datos y límites

Datos guardados en IndexedDB solo en el navegador y dispositivo actuales. No hay sincronización automática. Descarga respaldos regularmente. Para cambiar de dispositivo o dominio exporta e importa un respaldo. Borrar los datos del navegador elimina el inventario local.

Migra el almacenamiento local cv de Card Vault si está disponible en el mismo origen y la nueva base está vacía; conserva el original.

No incluye identificación automática, análisis IA, probabilidades de PSA 10 ni precios en vivo. Se eliminaron dependencias de claude.use. Los precios se registran manualmente. Revisa los anuncios y publícalos manualmente en eBay.

## Verificación

Sintaxis JavaScript validada. Prueba en navegador de creación, edición, persistencia después de recargar, generación de anuncio y ganancia ($40 - $20 - $5 = $15).
