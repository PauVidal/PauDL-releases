# PauDL · versiones

Aquí solo se publican los instaladores de **PauDL**, la extensión de Chrome para descargar vídeo y audio con yt-dlp. El código fuente no está en este repositorio.

## Instalar

1. Descarga `PauDL-Setup.exe` de la [última versión](https://github.com/PauVidal/PauDL-releases/releases/latest).
2. Ábrelo y pulsa **Sí**. No necesita permisos de administrador.
3. Sigue los pasos que te indica para cargar la extensión en Chrome.

## Actualizaciones

Desde la 0.3.5, PauDL comprueba aquí si hay una versión nueva y te avisa en su panel (o se instala sola, si lo eliges en *Sistema*). Cada instalador lleva su `PauDL-Setup.exe.sha256`, y PauDL no instala nada cuya huella no coincida.

## Privacidad

PauDL funciona en tu equipo y no recoge ni envía datos sobre ti, sobre lo que descargas ni sobre las páginas que visitas. Solo se conecta a internet para:

- **Descargar lo que le pides**, desde la web de origen, igual que lo haría tu navegador.
- **Buscar versiones nuevas** en este repositorio de GitHub, como mucho cada 6 horas. GitHub ve tu dirección IP y la versión de PauDL, como en cualquier visita a su web ([política de privacidad de GitHub](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement)).
- **Instalar o actualizar yt-dlp, FFmpeg, Deno y el PO Token**, solo cuando lo pides, desde sus repositorios oficiales en GitHub.

La configuración (carpeta de destino, preferencias) se guarda en tu equipo, en `%LOCALAPPDATA%\PauDL` y en el almacenamiento local de la extensión.

## Uso responsable

Eres responsable de lo que descargas y de cómo lo usas: respeta los derechos de autor y las condiciones de cada plataforma. Los detalles están en la [licencia](LICENSE.md).

## Licencia

- PauDL: [LICENSE.md](LICENSE.md). Uso gratuito; puedes compartir el instalador sin modificar. Sin garantía.
- Componentes de terceros: [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) y los textos completos en [licenses](licenses).

---

Pau Vidal
