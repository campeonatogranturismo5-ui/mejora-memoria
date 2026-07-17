# 📚 Memoria 30 Días — Entrenamiento Cognitivo

<div align="center">

![Memoria 30 Días](https://img.shields.io/badge/Programa-30%20D%C3%ADas-6366f1?style=for-the-badge&logo=bookstack&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-Sin%20dependencias-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Licencia](https://img.shields.io/badge/Licencia-MIT-22c55e?style=for-the-badge)
![Estado](https://img.shields.io/badge/Estado-Estable-22c55e?style=for-the-badge)

**Programa interactivo de entrenamiento de memoria basado en técnicas de memoria visual y mnemotecnia.**  
Un solo archivo HTML — sin instalación, sin servidor, sin conexión a internet.

[▶ Abrir App](#-cómo-usar) · [📋 Ver los 30 días](#-programa-completo) · [🐛 Reportar error](../../issues)

</div>

---

## ✨ ¿Qué es?

Una aplicación web completa contenida en **un único archivo `.html`** que guía al usuario durante **30 días** para desarrollar una memoria prodigiosa. Incluye ejercicios diarios cronometrados, seguimiento de progreso, sistema de rachas, estadísticas y un test final comparativo.

Basada en técnicas usadas por campeones mundiales de memoria:

| Técnica | Semana |
|---------|--------|
| 🖼️ Asociaciones Absurdas y Visualización | 1 |
| 🏛️ Método Loci / Palacio de la Memoria | 2 |
| 🔢 Sistema Fonético Mayor (00–99) | 3 |
| 🎯 Aplicación práctica en contextos reales | 4 |

---

## 🚀 Cómo usar

```
1. Descarga el archivo:  Memoria30Dias_Corregida.html
2. Ábrelo con cualquier navegador (Chrome, Firefox, Edge, Safari)
3. ¡Listo! No necesitas internet después de la primera carga
```

> **Sin instalación.** Sin npm, sin Python, sin servidor. Doble clic y funciona.

---

## 📅 Programa completo

### Semana 1 — Imágenes y Asociaciones
| Día | Título | Técnica |
|-----|--------|---------|
| 1 | Asociaciones Absurdas | Crear imágenes vívidas e ilógicas |
| 2 | Exageración de Tamaño | Modificar proporciones para retener |
| 3 | Sustitución Visual | Conceptos abstractos → imágenes concretas |
| 4 | Encadenamiento Directo | Conectar imágenes en secuencia |
| 5 | Método de la Historia | Narrativa para enlazar listas largas |
| 6 | Detalles Sensoriales | Color, sonido y tacto mental |
| 7 | Repaso Semanal | Evaluación de retención |

### Semana 2 — Colgaderos y Palacio de la Memoria
| Día | Título | Técnica |
|-----|--------|---------|
| 8 | Colgaderos por Rima | 1=pan, 2=tren, 3=pared… |
| 9 | Colgaderos por Forma | 1=lápiz, 2=cisne, 3=labios… |
| 10 | Casillero Corporal | Tu cuerpo como palacio inicial |
| 11 | Creación del Palacio | Diseñar ruta mental con habitaciones |
| 12 | Poblamiento del Palacio | Colocar imágenes en el recorrido |
| 13 | Recorrido Inverso | Dominar el palacio hacia atrás |
| 14 | Palacios Múltiples | Segunda ruta para información distinta |

### Semana 3 — Sistema Fonético y Números
| Día | Título | Técnica |
|-----|--------|---------|
| 15 | Sistema Fonético Básico | 0=S/Z, 1=T/D, 2=N, 3=M, 4=R… |
| 16 | Formando Palabras (00–09) | Consonantes + vocales → imágenes |
| 17 | Números de 4 Dígitos | Dos imágenes por número largo |
| 18 | Memorización de Teléfonos | Sistema fonético en números reales |
| 19 | Nombres y Rostros | Asociar nombres a rasgos físicos |
| 20 | Textos y Discursos | Conceptos clave en el palacio |
| 21 | Baraja de Cartas | 52 cartas con sistema fonético |

### Semana 4 — Aplicación Real y Consolidación
| Día | Título | Técnica |
|-----|--------|---------|
| 22 | Tareas Laborales | Palacio para organizar la jornada |
| 23 | Lista de Compras | 8+ ítems sin papel |
| 24 | Proveedores y Clientes | Nombre + producto + contacto |
| 25 | Mantenimiento del Vehículo | Puntos de revisión mecánica |
| 26 | Protocolos de Seguridad | Extintores, salidas, botiquines |
| 27 | Configuración de Repaso | Plan Ebbinghaus: 1, 3, 7, 14 días |
| 28 | Memorización Rápida | Reducir tiempo de codificación |
| 29 | Congelamiento de Imágenes | Fijar imágenes mentales permanentes |
| 30 | Evaluación Final | Test comparativo inicio vs. final |

---

## 🛠️ Características técnicas

- **📦 Un solo archivo** — todo el código en `memoria_corregida.html` (≈ 72 KB)
- **💾 Progreso local** — guarda con `localStorage`, sin cuenta, sin servidor
- **📊 Estadísticas** — gráfica de tiempo y precisión con Chart.js
- **🔥 Sistema de rachas** — motivación para no romper la cadena
- **🏅 Celebración de logros** — modal animado al completar cada día
- **🍞 Notificaciones toast** — feedback inmediato sin `alert()` bloqueantes
- **📱 Responsive** — funciona en móvil, tablet y escritorio
- **♿ Accesible** — navegación por teclado, contraste WCAG AA
- **🎨 Temas** — modo claro y oscuro incluido

---

## 🐛 Bugs corregidos respecto al original

| Bug | Descripción | Estado |
|-----|-------------|--------|
| `completeDay()` | El día siguiente nunca se desbloqueaba | ✅ Corregido |
| `closeSettings()` | El modal de ajustes no cerraba al hacer clic fuera | ✅ Corregido |
| Indicador de nivel | `inline-block` + `flex` incompatibles → `inline-flex` | ✅ Corregido |
| Temporizador | Formato incorrecto para tiempos > 59 s → ahora `MM:SS` | ✅ Corregido |
| `resetDay()` | No hacía nada útil, eliminada | ✅ Corregido |
| Racha (streak) | Condición `else if` redundante simplificada | ✅ Corregido |

---

## 📁 Estructura del repositorio

```
📦 memoria-30-dias
 ┣ 📄 Memoria30Dias_Corregida.html   ← App completa (abrir con navegador)
 ┗ 📄 README.md                      ← Esta documentación
```

---

## 🤝 Contribuir

1. Haz fork del repositorio
2. Crea tu rama: `git checkout -b mejora/nueva-funcion`
3. Haz commit: `git commit -m 'Añadir nueva función'`
4. Haz push: `git push origin mejora/nueva-funcion`
5. Abre un Pull Request

---

## 📄 Licencia

Distribuido bajo la licencia **MIT**. Puedes usarlo, modificarlo y distribuirlo libremente.

---

<div align="center">

Hecho con ❤️ · Basado en técnicas de memoria visual y mnemotecnia

**[⬆ Volver arriba](#-memoria-30-días--entrenamiento-cognitivo)**

</div>
