# Refugio Huellitas

Panel web adaptable para registrar y administrar mascotas en adopción.

## Funciones

- Registro de perros, gatos y otros animales, con código automático.
- Cinco perfiles de muestra con fotos ilustrativas en la primera visita; se pueden editar o eliminar.
- Galería de perfiles con fotografías, filtros por especie, edad y estado, búsqueda, favoritos y ficha individual.
- Carga de fotos reales optimizadas al registrar o editar una mascota.
- Seguimiento de adopción en tres estados: disponible, en proceso y adoptado, con fecha de actualización.
- Resumen de mascotas por especie y estado.
- Búsqueda por nombre, código o teléfono y filtros por especie y estado.
- Edición de datos, actualización de estado entre disponible/adoptado y eliminación confirmada.
- Almacenamiento ampliado en el navegador mediante IndexedDB, con importación automática de registros anteriores.

Abre `index.html` en un navegador moderno. Los cinco registros de muestra se cargan una sola vez cuando el navegador no tiene mascotas guardadas; esto también corrige sesiones que conservaron una lista vacía de una visita anterior. Se pueden editar o eliminar y reemplazar por información real. Mascotas y fotos se guardan en IndexedDB para ofrecer mucho más espacio que `localStorage`; los favoritos se guardan en el navegador. Los datos solo están disponibles en el dispositivo y navegador utilizados; esta versión no sincroniza datos entre usuarios ni dispositivos. Las fotos ilustrativas requieren conexión a internet.
