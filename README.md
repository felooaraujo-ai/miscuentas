# Mis Cuentas

App para anotar la plata que entra y sale, organizada en secciones propias. Pensada para el celular: se puede agregar a la pantalla de inicio.

- Cada persona crea su cuenta con mail y contraseña y ve solo sus datos.
- Montos guardados en pesos, con vista opcional en dólares según la cotización que cargues.

## Cómo funciona

- `index.html`: toda la app.
- `firebase-config.js`: datos públicos del proyecto de Firebase (Authentication + Firestore).
- `firestore.rules`: reglas de seguridad para pegar en la consola de Firebase.
- `manifest.webmanifest`, `sw.js` e íconos: permiten instalarla en el celular.
- `vendor/`: SDK de Firebase 10.12.2.

Se publica con GitHub Pages desde la rama `main`.
