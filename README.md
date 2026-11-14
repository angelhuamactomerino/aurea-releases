# Aurea Releases 🚀

Canal oficial y público de distribución y actualización continua para **Aurea: Tu Santuario de Enfoque y Éxito Académico**.

---

## 📥 Descarga Directa de la Última Versión

- **Última Versión:** `v0.2.4` (Build `32`)
- **Descargar APK Oficial:** [Aurea.apk](https://raw.githubusercontent.com/angelhuamactomerino/aurea-releases/main/apk/Aurea.apk)
- **Manifiesto de Versión:** [version.json](https://raw.githubusercontent.com/angelhuamactomerino/aurea-releases/main/version.json)

---

## ✨ Novedades en v0.2.4 (Build 32)

- **Corrección Exhaustiva de Inicio de Sesión y Firestore (Método del Elefante y Pez Dorado):**
  - **Solución al error `Failed to get document from server... local cache`:** Al cerrar y reabrir sesión con Google, Firestore implementa reintentos con retraso exponencial para permitir que la conexión gRPC y el token de autenticación se estabilicen.
  - **Recuperación Inteligente desde Caché Local:** Si el servidor no responde por problemas de red o latencia, la aplicación consulta la caché local persistente de Firestore del dispositivo, restaurando de inmediato los datos del usuario sin bloquear el acceso ni forzar cierres de sesión.
  - **Sesión Resiliente Offline:** Si no hay internet durante el login, la sesión permanece iniciada y los datos se sincronizan automáticamente con el servidor al recuperar la conexión.
  - **Cierre de Sesión Síncrono y Seguro:** Limpieza completa del estado de `CredentialManager` y prevención de subidas redundantes mediante una ventana de gracia post-sincronización (`remoteApplyGraceUntilEpoch`).

---

## 📚 Novedades Anteriores (v0.2.2 y previas)

- **Carga Automática y Rápida de Partida + Módulo Académico Depurado (v0.2.2):**
  - Consultas paralelas en Cloud Firestore dentro de una transacción atómica en Room, edición aislada de prácticas dentro de conjuntos y validación estricta de pesos, fechas y decimales.
- **Formicarium, Protección Monotónica y Acompañantes Universales:**
  - Catálogo de **43 especies nativas del Perú agrupadas en 14 géneros**, temas adaptativos (**Sistema**, **Claro**, **Dark Slate** y **Midnight OLED**), Pomodoro y Modo Búnker protegidos con `MonotonicClockGuard`, Charlote (26 pistas 1:1) y paquetes `.zip` universales.

---

## 🔄 Actualización In-App

La aplicación Aurea consulta automáticamente este repositorio público (`version.json`) para verificar si existe una nueva compilación (`manifest.versionCode > BuildConfig.VERSION_CODE`) y descargar el APK firmado directamente en el dispositivo sin necesidad de tokens o credenciales privadas de GitHub.

> [!NOTE]
> **Respaldo en Google Drive:** Siempre que se actualice este repositorio en GitHub, la versión correspondiente también se actualizará en **Google Drive > `Proyectos` > `Aurea`**.
