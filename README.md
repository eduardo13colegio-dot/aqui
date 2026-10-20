# Para mi niña bonita 💗

Página web romántica estática (HTML + CSS + JavaScript en un solo `index.html`). Funciona abriendo `index.html` directamente o publicada en GitHub Pages.

## Estructura

```
index.html          ← toda la página
assets/
  musica.mp3        ← (opcional) tu canción, pon aquí el archivo
  fotos/
    foto1.jpg ...   ← (opcional) sus fotos
```

## Qué personalizar (todo está al inicio del `<script>` en index.html, busca `CONFIG`)

| Qué | Dónde |
|---|---|
| Nombre | `NOMBRE: 'Esthefany'` |
| Fecha de aniversario (contador) | `FECHA_INICIO: ''` → por ejemplo `'2024-03-15'`. Vacío = el contador no se muestra |
| Música | Copia tu canción como `assets/musica.mp3`. Si no existe, el botón se oculta solo |
| Fotos | Copia las fotos a `assets/fotos/` y escribe la ruta en `FOTOS`, por ejemplo `src: 'assets/fotos/foto1.jpg'` |
| Textos de las fotos | `texto:` dentro de cada foto |
| Mensajes escondidos | `SECRETOS` |
| Carta, tarjetas y frases | Directamente en el HTML (busca los comentarios con ✏️) |

⚠️ GitHub Pages distingue mayúsculas: `Foto1.JPG` no es lo mismo que `foto1.jpg`. Usa nombres en minúsculas y sin espacios.

## Publicar en GitHub Pages

1. Entra a <https://github.com> e inicia sesión.
2. Arriba a la derecha pulsa **+ → New repository**. Ponle un nombre (por ejemplo `para-esthefany`), márcalo como **Public** y pulsa **Create repository**.
3. En el repositorio nuevo pulsa **uploading an existing file** (o **Add file → Upload files**).
4. Arrastra `index.html` y la carpeta `assets` (con tus fotos/música si ya las tienes). Pulsa **Commit changes**.
5. Ve a **Settings → Pages**. En **Build and deployment → Source** elige **Deploy from a branch**, en **Branch** elige `main` y carpeta `/ (root)`, y pulsa **Save**.
6. Espera 1–2 minutos y recarga esa página: arriba aparecerá el enlace, del tipo `https://TU-USUARIO.github.io/para-esthefany/`.

Para cambiar algo después, edita el archivo en GitHub (icono del lápiz) o vuelve a subirlo; la página se actualiza sola en uno o dos minutos.

> Nota: si el repositorio es público, cualquiera con el enlace puede verlo. La página incluye `noindex` para que no aparezca en buscadores.
