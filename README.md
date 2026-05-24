# Sabri Zeta — Link Page

## 📁 Archivos incluidos
- `index.html` — página principal (logo de perfil ya embebido)
- `SZ-1x1-Mini.jpg` — logo SZ
- `artwork.jpg` — imagen de arte (fallback)
- `README.md` — este archivo

## 🌐 Archivos externos (ya cargados desde URL pública)
Los siguientes assets se cargan directamente desde sus URLs:

| Asset | URL |
|---|---|
| Foto de perfil | LinkedIn CDN |
| Imagen artwork card | https://i.postimg.cc/Jn0JKTcn/artwork.webp |
| Imagen Pinterest pin | https://i.postimg.cc/cCHSv3Sj/Save-Clip-App-...jpg |
| GIF Tomato (Dribbble) | https://cdn.dribbble.com/userupload/38223385/file/original-47b2cc4bd373775dfed3fca0ea675fce.gif |
| Video Showreel | Vimeo 724285373 |

## 📦 Para subir a un hosting
1. Sube todos los archivos de esta carpeta a tu servidor / Netlify / Vercel / GitHub Pages
2. La página principal es `index.html`
3. Asegurate de que el dominio tenga HTTPS para que el Vimeo embed funcione

## 🎬 Video TikTok animation
El video de animación (cuadro inferior) tiene una URL con firma temporal de AWS.
Para hacerlo permanente:
1. Descargá el video desde TikTok: https://www.tiktok.com/@sabriszeta/video/7231754468000288006
2. Subí el archivo `.mp4` a tu hosting con el nombre `tiktok-anim.mp4`
3. Reemplazá la URL larga en el HTML por `tiktok-anim.mp4`

## 🌍 Deploy rápido (gratis)
- **Netlify**: arrastrá la carpeta en https://app.netlify.com/drop
- **GitHub Pages**: subí al repo y activá Pages en Settings
- **Vercel**: conectá el repo o usá `vercel --prod`
