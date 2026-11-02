# Roam — APK Android de pruebas

[Descargar la actualización de seguridad para Android](https://github.com/sezalazar/roam-android-releases/releases/download/android-security-2026-11-02-3f9afb1/roam-3f9afb1-expo58-android-js-tabs.apk)

Abrí el enlace desde Android, descargá el APK e instalalo como actualización de Roam. Si Android lo solicita, habilitá instalar desde esa fuente para esta descarga. Conservá la app instalada: no hace falta desinstalar ni borrar sus datos. Si aparece un conflicto de firma o instalación, guardá el mensaje antes de hacer cambios.

Esta entrega incorpora **OkHttp 5.5.1** con el bloqueo de certificados comprometidos. Sustituye los APK de prueba anteriores; cada dispositivo debe instalar este archivo manualmente. La descarga no actualiza equipos por sí sola y esta app no tiene actualización automática configurada.

## Identificación

- Archivo: `roam-3f9afb1-expo58-android-js-tabs.apk` (109.818.107 bytes).
- SHA-256: `b3e5d5f698b838d9c64a2d7ea4925bceb10edd9eea1e50334e4469d80b390fe0`.
- Package: `dev.roam.replica`; versión Android 1.0.0, versionCode 1.
- Android 7.0/API 24 o posterior; arm64-v8a, armeabi-v7a, x86 y x86_64.
- Certificado de pruebas conservado: SHA-256 `fac61745dc0903786fb9ede62a962b399f7348f0bb6f899b8332667591033b9c`.
- Fuente auditada: commit `3f9afb11a2bfbe2d441ae423543b75fec156ae9f` del proyecto local Roam.

## Qué se verificó

El mismo APK pasó una auditoría independiente sobre emulador Android: autenticación de prueba, Home con datos reales, reapertura, detalle y Back, Search sin envío, Trips, Profile y logout. También se comprobó resolución de toda la familia OkHttp a 5.5.1, bloqueo de certificados en release, firma e integridad. No necesita Metro, QR ni servidor de desarrollo.

## Límites de esta versión

Es una versión interna de pruebas, firmada con el certificado de pruebas existente y con Clerk de desarrollo; no es una publicación en Play Store ni una versión de producción. Necesita Internet y una cuenta propia habilitada para pruebas. No se probó en un teléfono físico. SSO Google/Apple, iOS e IA normal TypeSafe/Jev siguen pendientes; Ask puede usar respuestas de respaldo. Los favoritos duran durante la sesión. Book muestra un resumen y no cobra ni crea reservas reales. La réplica integral todavía tiene criterios pendientes.

## Procedencia y licencia

Proyecto de réplica basado en [jsmastery-pro/airbnb-clone](https://github.com/jsmastery-pro/airbnb-clone). Se conserva la licencia MIT original en [LICENSE](LICENSE). Este repositorio sólo distribuye el APK y sus instrucciones; no contiene credenciales, datos privados ni el historial local de trabajo.
