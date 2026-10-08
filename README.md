# Refugio Huellitas

Panel web adaptable para registrar y administrar mascotas en adopción.

## Funciones

- Registro de perros, gatos y otros animales, con código automático.
- Galería de perfiles con fotografías, filtros por especie, edad y estado, búsqueda, favoritos y ficha individual.
- Carga de fotos reales optimizadas al registrar o editar una mascota.
- Seguimiento de adopción en tres estados: disponible, en proceso y adoptado, con fecha de actualización.
- Resumen de mascotas por especie y estado.
- Búsqueda por nombre, código o teléfono y filtros por especie y estado.
- Edición de datos, actualización de estado entre disponible/adoptado y eliminación confirmada.
- Almacenamiento ampliado en el navegador mediante IndexedDB, con importación automática de registros anteriores.

Abre `index.html` en un navegador moderno. La plataforma comienza vacía para que registres tus propios animales. Al actualizar, elimina automáticamente los cinco perfiles de demostración anteriores y conserva las mascotas reales que hayas agregado. Mascotas y fotos se guardan en IndexedDB; los favoritos se guardan en el navegador. Los datos solo están disponibles en el dispositivo y navegador utilizados; esta versión no sincroniza datos entre usuarios ni dispositivos. Las fotos ilustrativas que aparecen al registrar una mascota sin foto requieren conexión a internet.
