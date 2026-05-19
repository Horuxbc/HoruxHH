# INSTRUCCIONES PARA SUBIR EL DASHBOARD

## Archivos en este paquete
- `dashboard.html` - Dashboard final con todas las funcionalidades
- `handoff_sesion_19may2026.md` - Contexto completo de la sesión

---

## Cómo subir a GitHub (desde la interfaz web)

### Paso 1: Ir al repositorio
Entra a https://github.com/horuxbc/Horux

### Paso 2: Localizar dashboard.html actual
En la lista de archivos del repo, click en `dashboard.html`

### Paso 3: Editar
Click en el ícono de lápiz (✏️ "Edit this file") arriba a la derecha

### Paso 4: Reemplazar contenido
1. Selecciona TODO el contenido actual (Ctrl+A)
2. Bórralo (Delete)
3. Abre el archivo `dashboard.html` que descargaste con Notepad o similar
4. Selecciona todo (Ctrl+A) y copia (Ctrl+C)
5. Pega en GitHub (Ctrl+V)

### Paso 5: Commit
1. Baja al final de la página
2. En "Commit message" escribe: `Update dashboard: nuevo diseño con KPIs y filtros`
3. Click en "Commit changes" (botón verde)

### Paso 6: Esperar publicación
GitHub Pages tarda 60-90 segundos en publicar.

### Paso 7: Verificar
Abre en navegador (mejor incógnito Ctrl+Shift+N):
```
https://horuxbc.github.io/Horux/dashboard.html
```

---

## Credenciales del login

| Usuario | Contraseña |
|---|---|
| talento@horux.mx | Talento2026! |
| Luis@horux.mx | Talento2026! |

---

## Funcionalidades incluidas

### Login con fondo degradado
- 2 usuarios configurados
- Sesión guardada (no tienes que volver a entrar cada vez)
- Botón "Cerrar sesión" en el sidebar
- Fondo verde Horux con HORUX gigante difuminado de marca de agua

### Dashboard
- Status line con cobrado vs PE
- 6 KPIs clickeables (cada uno abre modal con detalle):
  1. Cobrado vs PE
  2. Margen del mes
  3. Pipeline ponderado
  4. Colocaciones del mes
  5. Cobranza vencida
  6. Carga por headhunter

### Composición de cartera
- Gráfica de barras horizontales
- Toggle entre "Por número" y "Por monto"
- 5 categorías: Operativa · Mando medio · Ejecutiva · Especialista · Administrativo

### Vacantes activas
- Vistas rápidas: Todas · Mayor antigüedad · Solo activas · Solo ternas · Solo propuestas · De Anayelli · De Carla
- Filtros avanzados (ordenar por días/monto/cliente, filtrar por tipo)
- Resumen automático arriba (total, honorarios, pendiente, días promedio)
- 25 vacantes activas (no muestra On Hold ni Canceladas)
- Incluye las 4 nuevas TRAINSA:
  - Mecánico A · $8,000
  - Mecánico B · $8,000
  - Remolquero · $8,000
  - Gerente Operaciones · $86,229

---

## Para regresar al dashboard anterior

Si algo sale mal:
1. Entra al repo en GitHub
2. Click en "Commits" arriba
3. Busca el commit anterior al cambio
4. Click en "..." y "Revert"

GitHub mantiene historial de versiones automático.

---

## Para próxima sesión

- Conectar al Google Sheet (back office)
- Diseñar secciones Clientes y Razones Sociales
- Agregar capa de seguridad real (Apps Script)
- Clasificar las vacantes históricas por tipo
