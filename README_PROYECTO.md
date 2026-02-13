# 💫 Haru - Página Web Romántica

Una página web especial creada para una declaración romántica bajo las estrellas.

## ✨ Características

- **Cielo estrellado animado** con efecto de parpadeo
- **Constelaciones de Géminis y Acuario** conectadas por un corazón
- **Mensaje romántico** que aparece después de la animación
- **Frases diarias románticas** fáciles de agregar
- **Música de fondo** de Taylor Swift
- **Footer personalizable** para el desarrollador

## 🚀 Inicio Rápido

```bash
# Instalar dependencias
pnpm install

# Iniciar servidor de desarrollo
pnpm dev

# Construir para producción
pnpm build
```

## 📝 Cómo agregar frases diarias

1. Abre el archivo `src/data/phrases.json`
2. Agrega un nuevo objeto con la fecha y la frase:

```json
{
  "date": "2026-02-01",
  "phrase": "Tu nueva frase romántica aquí."
}
```

La página mostrará automáticamente la frase correspondiente al día actual.

## 🎵 Configurar la música

1. Ve a la carpeta `public/music/`
2. Lee el archivo `README.md` dentro de esa carpeta
3. Descarga una canción de Taylor Swift (MP3)
4. Renómbrala a `taylor-swift-song.mp3` y colócala allí

### Canciones recomendadas:
- Lover
- Enchanted
- Sweet Nothing
- Timeless
- You Are In Love

## 🎨 Personalizar el Footer

Edita el archivo `src/components/Footer.astro`:

1. Reemplaza `[Tu Nombre]` con tu nombre
2. Agrega tu logotipo en el div `.logo-placeholder`
3. Actualiza los enlaces sociales (GitHub, LinkedIn, Portfolio)

## 🌟 Estructura del Proyecto

```
/
├── public/
│   └── music/          # Coloca aquí tu archivo de música
├── src/
│   ├── components/
│   │   ├── StarryBackground.astro    # Fondo estrellado
│   │   ├── Constellations.astro      # Animación de constelaciones
│   │   ├── RomanticMessage.astro     # Mensaje principal
│   │   ├── DailyPhrases.astro        # Sección de frases
│   │   └── Footer.astro              # Footer personalizable
│   ├── data/
│   │   └── phrases.json              # Tus frases románticas
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

## 💡 Tips

- Las constelaciones aparecen automáticamente al cargar la página
- Después del mensaje romántico, hay un scroll automático a las frases
- El reproductor de música está en la esquina inferior derecha
- Todas las animaciones están hechas con GSAP
- El diseño es completamente responsive

## 🎯 Próximos pasos

1. Agrega más frases en `phrases.json`
2. Personaliza el footer con tus datos
3. Agrega tu canción favorita de Taylor Swift
4. Ajusta los colores si lo deseas (rosa: #ffb6c1)
5. ¡Comparte con esa persona especial! 💕

## 🛠️ Tecnologías

- [Astro](https://astro.build/)
- [GSAP](https://greensock.com/gsap/)
- Canvas API para el cielo estrellado
- CSS moderno con animaciones

---

**Hecho con 💙, código y mucho amor**
