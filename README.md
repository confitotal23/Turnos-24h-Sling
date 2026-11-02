# 📅 Gestor de Turnos 24h (PWA)

Aplicación web progresiva (**PWA**) diseñada para gestionar turnos rotativos de guardias de 24 horas (8:00h a 8:00h) entre un equipo de 6 personas.

---

## 🚀 Características Principales

- **Calendario Rotativo Continuo:** Generación automática e infinita del cuadrante de turnos basado en una secuencia rotativa de 6 días.
- **Validación de Permutas en Tiempo Real:** 
  - Comprueba automáticamente si el solicitante realmente tiene guardia en la fecha seleccionada.
  - Verifica si el día solicitado al compañero coincide con su turno real.
  - Bloquea solicitudes erróneas mostrando avisos explicativos.
- **Instalable como PWA (App Móvil):** Compatible con Chrome/Android y Safari/iOS ("Añadir a la pantalla de inicio") con icono personalizado.
- **Diseño Adaptativo Móvil (Portrait):** Optimizado para consultar el calendario cómodamente en vertical sin necesidad de girar el dispositivo.
- **Sistema de Notificaciones e Historial:**
  - Badge dinámico en la campana superior con conteo de solicitudes pendientes.
  - Registro de cambios y permutas (Pendientes, Aprobadas y Rechazadas).
- **Modo Administrador:** Permite forzar ajustes manuales o resolver solicitudes directamente en el cuadrante.

---


## 🛠️ Instalación y Uso

No requiere servidor ni instalación de dependencias backend.

1. Abre la URL pública de **GitHub Pages** desde tu navegador.
2. En tu móvil, abre el menú de opciones de Chrome / Safari y selecciona **"Añadir a la pantalla de inicio"** para usarla como una app nativa.

---

## 💻 Tecnologías Utilizadas

- **HTML5 & JavaScript ES6** (Single File App)
- **Tailwind CSS** (Estilos vía CDN)
- **Lucide Icons** (Iconografía vectorial)
- **LocalStorage** (Persistencia de datos local)
