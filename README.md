# Espacio Inmobiliario — beta editorial
Frontend React + Vite + JavaScript, Tailwind v4, Zustand y React Hook Form + Zod. Estructura basada en el estándar V3 adjunto. Sin backend, autenticación ni APIs.

## Desarrollo
Desde la raíz: `npm install` y `npm run dev`.
Compilar: `npm run build`. Salida estática: `dist`.

## Funciones
Catálogo con filtros y favoritos, ficha editorial con galería, administración local de altas/ediciones/borrado/borradores, carga y compresión de imágenes, selección de portada. Persistencia localStorage, exclusivamente en el navegador actual. No hay acceso administrativo protegido ni publicación a una base de datos. Las imágenes se limitan a ocho por propiedad.

## Referencias y datos
Instagram bloqueó la lectura automatizada del perfil y del post. La captura proporcionada fundamenta únicamente 1 dormitorio, ambientes separados, placar y ventiladores, unidades 5C/4C ARS 550.000, 2B/3B ARS 600.000 y expensas ARS 110.000. No se verificaron vigencia, ubicación exacta ni disponibilidad. Las demás propiedades son demostrativas. Fotografías ilustrativas de Unsplash: no representan los inmuebles reales. Marca tipográfica conceptual y paleta interpretada de la captura, pendientes de activos oficiales.

No se añadieron Flask, pagos, Auth0, Redis, Sentry ni infraestructura backend del generador porque esta entrega es exclusivamente visual. La futura API puede incorporarse en frontend/src/api conservando la interfaz del store.
