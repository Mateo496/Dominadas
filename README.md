# Dominadas 7 → 12

App Android (WebView) con la rutina full body de 10 semanas para pasar de 7 a 12 dominadas, con cronómetro guiado por voz.

- La página está en `app/src/main/assets/index.html`.
- Cada vez que se sube un cambio a `main`, GitHub Actions compila el APK firmado y lo publica en **Releases**.
- La clave de firma está en `keystore/`. Si se cambia, las actualizaciones ya no se podrán instalar encima de la versión anterior (y se perdería el progreso guardado).
