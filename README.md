# Aurea Releases 🚀

Canal oficial y público de distribución y actualización continua para **Aurea: Tu Santuario de Enfoque y Éxito Académico**.

---

## 📥 Descarga Directa de la Última Versión

- **Última Versión:** `v0.2.2` (Build `30`)
- **Descargar APK Oficial:** [Aurea.apk](https://raw.githubusercontent.com/angelhuamactomerino/aurea-releases/main/apk/Aurea.apk)
- **Manifiesto de Versión:** [version.json](https://raw.githubusercontent.com/angelhuamactomerino/aurea-releases/main/version.json)

---

## ✨ Novedades hasta v0.2.2 (Build 30)

- **Carga Automática y Rápida de Partida + Autosync Offline:**
  - Inicio de sesión unificado con Google (`CredentialManager` + respaldo OAuth) desde Bienvenida, Inicio y Ajustes que descarga y fusiona automáticamente la partida previa en paralelo dentro de una transacción atómica en Room.
  - Sincronización automática en Cloud Firestore (`users/{uid}`) cada vez que cambian los datos locales con conexión a Internet, más cola pendiente (`PendingOffline`) que actualiza la nube automáticamente al recuperar red o volver al primer plano.
- **Módulo Académico Depurado:**
  - Edición de evaluaciones dentro de un conjunto limitada exclusivamente a nombre y nota (preservando la configuración del grupo y evitando recompensas duplicadas en la colonia al editar notas).
  - Validación de fechas reales en ciclos, pesos y decimales (`.` y `,`), eliminación en cascada de ciclos/conjuntos con confirmaciones de seguridad, y ausencia de prefijos duplicados ni elementos redundantes.
- **Autenticación Firebase, Formicarium y Protección Monotónica (`MonotonicClockGuard`):**
  - Registro y autenticación directa con Google y Correo/Contraseña en Firebase Authentication (`aurea-10d05`), más catálogo de **43 especies nativas del Perú agrupadas en 14 géneros**, temas reactivos (**Sistema**, **Claro**, **Dark Slate** y **Midnight OLED**), Pomodoro resiliente y Room Schema v10.
- **Horarios y Acompañantes Universales (1:1):**
  - **Charlote** (26 pistas de voz 1:1 y retratos dinámicos) y sistema universal de acompañantes importables/exportables en `.zip`.

---

## 🔄 Actualización In-App

La aplicación Aurea consulta automáticamente este repositorio público (`version.json`) para verificar si existe una nueva compilación (`manifest.versionCode > BuildConfig.VERSION_CODE`) y descargar el APK firmado directamente en el dispositivo sin necesidad de tokens o credenciales privadas de GitHub.

> [!NOTE]
> **Respaldo en Google Drive:** Siempre que se actualice este repositorio en GitHub, la versión correspondiente también se actualizará en **Google Drive > `Proyectos` > `Aurea`**.
