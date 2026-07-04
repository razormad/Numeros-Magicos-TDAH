# 🌟 Números Mágicos

> **Aprender jugando, sin prisa.**  
> Una Progressive Web App (PWA) diseñada para niños y niñas de 3 a 8 años, especialmente pensada para quienes presentan TDA, TDAH y otras necesidades especiales de atención.

---

## 📖 Descripción

**Números Mágicos** es una aplicación educativa 100 % offline que transforma el aprendizaje de matemáticas básicas en una experiencia lúdica, calmada y accesible. No requiere conexión a Internet, no contiene publicidad ni compras integradas, y puede instalarse en cualquier dispositivo Android o iOS como si fuera una app nativa.

El diseño sigue principios de **accesibilidad cognitiva** y **diseño universal para el aprendizaje (DUA)**, priorizando la reducción de la carga atencional, la retroalimentación inmediata y la autonomía del niño.

---

## ✨ Características principales

### 🎮 6 juegos educativos
| Juego | Edad recomendada | Habilidad trabajada |
|---|---|---|
| 🚂 **El Tren** | 5 – 8 años | Series numéricas (+1, +2, +3, +5, +10) |
| 🍎 **Contar** | 3 – 5 años | Correspondencia número-cantidad |
| ⚖️ **Mayor o Menor** | 5 – 7 años | Comparación numérica |
| ➕ **Suma Mágica** | 6 – 8 años | Sumas visuales con emojis |
| 🌈 **Patrones** | 3 – 6 años | Secuencias lógicas de colores |
| 🧠 **Memoria** | 5 – 8 años | Atención selectiva y memoria de trabajo |

### 🧠 Adaptaciones para TDA / TDAH y necesidades especiales
- **Rondas ultracortas**: cada ronda consta de solo 3 ejercicios (máximo 2 minutos).
- **Sin temporizador**: elimina la ansiedad por el tiempo.
- **Saltar sin penalización**: el niño puede avanzar si se bloquea, sin frustración.
- **Pistas ilimitadas**: guían paso a paso sin dar la respuesta directa.
- **Botón de respiro 🌿**: ejercicio de respiración guiada para momentos de sobreestimulación.
- **Retroalimentación inmediata**: celebraciones visuales (confeti) y sonidos suaves al acertar.
- **Instrucciones por voz**: lectura automática de enunciados (opcional).
- **Modo tranquilo**: reduce animaciones para niños sensibles a estímulos visuales.
- **Alto contraste**: mejora la legibilidad para problemas visuales.
- **Progreso persistente**: las estrellas ganadas se guardan entre sesiones (`localStorage`).

### 📱 Instalación como app nativa (PWA)
- Funciona 100 % **offline** (sin servidor ni Internet).
- Se instala en Android/iOS con un icono propio y pantalla completa.
- Sin barras de navegador ni distracciones externas.

---

## 🚀 Cómo empezar

### Opción 1: Abrir directamente en el navegador
1. Descarga el archivo `mundo_numeros.html`.
2. Haz doble clic o arrástralo a tu navegador (Chrome, Edge, Safari, Firefox).
3. ¡Listo! La app funciona inmediatamente.

### Opción 2: Instalar en Android (recomendado)
1. Transfiere el archivo a tu teléfono (por correo, cable USB, Drive, etc.).
2. Abre el archivo con **Google Chrome**.
3. Toca el menú (⋮) → **"Añadir a pantalla de inicio"** o **"Instalar app"**.
4. Aparecerá el icono **🌟 Números Mágicos** junto a tus apps.

### Opción 3: Instalar en iOS (iPhone / iPad)
1. Abre el archivo en **Safari**.
2. Toca el botón **Compartir** (📤) → **"Añadir a pantalla de inicio"**.
3. Confirma y aparecerá el icono en tu pantalla de inicio.

---

## 📁 Estructura del proyecto

```
.
├── mundo_numeros.html      # App completa (PWA, monolito)
├── NOMBRE_APP.md           # Notas sobre la marca
├── README.md               # Este archivo
└── assets/                 # (Opcional) Iconos y capturas de pantalla
    ├── icon-192.png
    ├── icon-512.png
    └── screenshots/
```

> **Nota**: La app está contenida en un único archivo HTML para facilitar su distribución en entornos con recursos limitados (colegios, familias, terapeutas).

---

## 🛠️ Tecnologías

- **HTML5** semántico y accesible
- **CSS3** con variables, flexbox, grid y animaciones suaves
- **Vanilla JavaScript** (ES5 compatible para máxima compatibilidad con navegadores antiguos)
- **Web Speech API** (síntesis de voz, opcional)
- **Web Audio API** (efectos de sonido suaves, opcional)
- **LocalStorage API** (persistencia de progreso)
- **PWA Manifest** (instalación nativa)

---

## 🎨 Principios de diseño inclusivo

1. **Perceptible**: colores vivos, formas grandes, alto contraste opcional, voz integrada.
2. **Operable**: botones grandes (mínimo 60×60 px), sin gestos complejos, navegación táctil simple.
3. **Comprensible**: instrucciones cortas, pictogramas, lenguaje sencillo.
4. **Robusto**: funciona en navegadores antiguos, sin dependencias externas, sin conexión obligatoria.

---

## 🤝 Cómo contribuir

¡Toda ayuda es bienvenida! Algunas ideas:

- 🌍 Traducciones a otros idiomas.
- 🎨 Nuevos temas visuales (animales, espacio, océano...).
- 🎵 Música de fondo relajante opcional.
- 📊 Panel de seguimiento para padres o terapeutas.
- 🧩 Nuevos juegos (restas, relojes, formas geométricas, dinero...).
- ♿ Mejoras de accesibilidad (navegación por teclado, lectores de pantalla).

1. Haz un **fork** del repositorio.
2. Crea una rama: `git checkout -b feature/nueva-funcionalidad`.
3. Realiza tus cambios y haz commit: `git commit -m 'Añade: nueva funcionalidad'`.
4. Sube la rama: `git push origin feature/nueva-funcionalidad`.
5. Abre un **Pull Request**.

---

## 📜 Licencia

Este proyecto está licenciado bajo la **MIT License**.

```
MIT License

Copyright (c) 2026 Números Mágicos Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Agradecimientos

- A las familias, educadores y terapeutas que validaron el diseño en entornos reales.
- A la comunidad de código abierto por las herramientas que hacen posible proyectos como este.
- A los pequeños usuarios que inspiran cada mejora con su curiosidad y su sonrisa.

---


**⭐ Si te gusta el proyecto, dale una estrella en GitHub y compártelo con quien pueda necesitarlo.**

*Hecho con 💜 para los pequeños grandes aprendices.*


