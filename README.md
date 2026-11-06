# Magic TV — compilación automática para Android 11

## Compilar APK con GitHub Actions (sin Android Studio)

1. Inicia sesión o crea una cuenta en GitHub.
2. Crea un repositorio nuevo, por ejemplo `MagicTV`.
3. Sube **todos los archivos y carpetas** de este ZIP al repositorio (incluida `.github/workflows/build.yml`).
4. Abre la pestaña **Actions** del repositorio.
5. Selecciona **Build Magic TV APK** y pulsa **Run workflow** (o espera a que corra tras subir los archivos).
6. Cuando el trabajo termine con marca verde, entra en la ejecución y busca **Artifacts**.
7. Descarga `MagicTV-debug-apk`; dentro estará `app-debug.apk`.

## Instalar en Magcubic HY300 Pro

1. Copia `app-debug.apk` a una memoria USB o al proyector.
2. Abre el administrador de archivos y pulsa el APK.
3. Si Android lo solicita, permite instalar aplicaciones de esa fuente.
4. Instala y abre **Magic TV**.

## Notas
- APK debug para pruebas; no es una versión firmada para distribución comercial.
- Android 11 compatible (minSdk 23).
- El reproductor reproduce streams HTTP(S) compatibles (p. ej. HLS/M3U8); todavía no trae una parrilla de canales.
- Usa solo streams legales/autorizados.
