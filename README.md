# CVcopyPaste Dashboard

<img width="750" height="500" alt="Preview" src="https://github.com/user-attachments/assets/326ac45f-f9de-44c4-9aef-daa64b24f1df" />

## Descripción
Aplicación web para **centralizar y copiar rápidamente** la información que se usa en postulaciones laborales.

Surge de un problema real: al aplicar a distintos trabajos siempre termino buscando y copiando las mismas cosas  
(links, datos personales, textos).  
Esta app las guarda en un solo lugar y permite **copiarlas con un click**, manteniendo además un historial de lo enviado.

> **Nota:** esta primera versión guarda todo localmente (local-first). La idea es que, una vez terminado el MVP, se pueda agregar persistencia con backend sin cambiar las vistas principales.

---

## Qué hace la app
- Guarda datos personales y links importantes
- Guarda textos reutilizables (bio, mensaje al recruiter, cover letter)
- Permite registrar postulaciones como historial personal
- Copia cualquier bloque de información con un click
- Funciona sin backend (guardado local)
- Permite exportar e importar los datos (JSON)

---

## Concepto
La app se basa en dos ideas simples:

**1) Información genérica reutilizable**  
Datos que se repiten en casi todas las postulaciones y no cambian (pero pueden editarse si algo cambia).

**2) Historial de lo enviado**  
Registro personal de qué información se usó en cada postulación, sin hacer seguimiento del proceso de selección.

---

## Funcionalidades (MVP)
- Perfil base con datos personales, links y bios
- Historial de postulaciones enviadas
- Modo copy / paste por bloques + “Copiar todo”
- Búsqueda por empresa o puesto
- Guardado local + export/import JSON

---

## Stack
- React
- Vite
- React Router
- localStorage
- Netlify

---

## Motivación
Proyecto personal creado para resolver un problema cotidiano al buscar trabajo,
priorizando simplicidad, utilidad real y posibilidad de escalar a futuro.
