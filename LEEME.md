# Spelling Bee 2026 — 3ro EGB

App para practicar las 150 palabras de la lista de la escuela: el niño elige un dibujo,
escucha la palabra, la deletrea en voz alta y recibe 👍 o 👎 con la corrección.

## Archivos

| Archivo | Para qué |
|---|---|
| `index.html` | La app completa (palabras, dibujos y código en un solo archivo) |
| `apple-touch-icon.png` | Ícono para la pantalla de inicio del iPhone/iPad |
| `icon-192.png`, `icon-512.png`, `manifest.webmanifest` | Ícono y nombre para otros navegadores |

## 1. Subirla a GitHub Pages

1. En github.com, crea un repositorio **público** (por ejemplo `spelling-bee`).
   GitHub Pages gratis solo publica repositorios públicos.
2. **Add file › Upload files**, arrastra los 5 archivos de arriba (no hace falta subir este LEEME) y pulsa **Commit changes**.
3. **Settings › Pages › Build and deployment**: Source = *Deploy from a branch*, Branch = `main` y carpeta `/ (root)`. Guarda.
4. En uno o dos minutos la app queda en `https://TU-USUARIO.github.io/spelling-bee/`.

GitHub Pages usa HTTPS, que es obligatorio para que Safari permita el micrófono.

## 2. Anclarla en el iPad o iPhone

1. Abre el enlace en **Safari**.
2. Botón **Compartir** › **Agregar a pantalla de inicio**.
3. **Deja desactivado «Abrir como app web»** y toca **Agregar**.
   iOS no permite el reconocimiento de voz dentro de las apps web ancladas; con esa opción
   apagada el ícono abre la app en Safari y el micrófono funciona.
4. La primera vez que toque el micrófono, Safari pedirá permiso para el micrófono y el
   reconocimiento de voz: acepta los dos.

## 3. Requisitos del dispositivo

- **Siri y Dictado activados**: Ajustes › General › Teclado › Activar Dictado.
- **Internet**: el reconocimiento de voz de Apple suele necesitar conexión.
- Si el iPad tiene **Tiempo en pantalla** con restricciones, revisa que Siri y Dictado estén permitidos.

Si algo falla, en la app: ⚙️ Ajustes › **Probar micrófono** muestra exactamente lo que entiende
el dispositivo. Y siempre está el **teclado de letras** en la pantalla de práctica.

## 4. Cómo se usa

- **Elige una palabra** del panel (por hojas, como en la lista impresa) o usa **Reto de 10 palabras**.
- 🔊 Oír · 🐢 Lento · 💬 Oración con la palabra · 🇪🇨 Significado en español · 👀 Ver la palabra.
- Toca el **micrófono** y deletrea **con las letras en inglés y una pausita entre letras**:
  «C… A… T». Puede decir la palabra antes y después, como en el concurso: «cat, C-A-T, cat».
  Para letras repetidas también vale «double P».
- Al terminar, toca otra vez el micrófono (o espera unos segundos en silencio).
- Una palabra queda **dominada** cuando la deletrea bien dos veces seguidas sin usar «Ver».
- **Repasar errores** junta las palabras que salieron mal la última vez.

El progreso (estrellas, días seguidos, panal) se guarda en el propio dispositivo, dentro de
Safari. Si se borran los datos de Safari, se borra el progreso.

## 5. Actualizar

Para cambiar algo, sube el nuevo `index.html` al mismo repositorio (reemplaza el anterior).
El progreso del niño no se pierde.
