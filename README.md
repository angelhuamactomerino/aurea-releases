# Aurea Releases 🚀

Canal oficial y público de distribución y actualización continua para **Aurea: Tu Santuario de Enfoque y Éxito Académico**.

---

## 📥 Descarga Directa de la Última Versión

- **Última Versión:** `v0.2.3` (Build `31`)
- **Descargar APK Oficial:** [Aurea.apk](https://raw.githubusercontent.com/angelhuamactomerino/aurea-releases/main/apk/Aurea.apk)
- **Manifiesto de Versión:** [version.json](https://raw.githubusercontent.com/angelhuamactomerino/aurea-releases/main/version.json)

---

## ✨ Novedades en v0.2.3 (Build 31)

- **Cuenta Exclusiva con Google y Perfil Inicial Personalizable:**
  - Todo inicio de sesión y vinculación de cuenta ahora se realiza exclusivamente mediante **Google** (`CredentialManager` + respaldo OAuth), eliminando formularios manuales.
  - Al entrar por primera vez (con Google o como Invitado) puedes elegir tu **nombre de usuario y foto de perfil** (galería, foto de Google, avatares de Aurea o iniciales), y editarlos en cualquier momento desde **Ajustes**.
- **Sincronización 100% Automática y Offline-Resiliente:**
  - Se eliminaron los botones manuales de guardado y carga: todo avance se respalda en automático al existir conexión; si no hay internet, la sesión permanece abierta y los cambios se suben en cuanto vuelve la red.
- **Cerrar Sesión y Reinicio Limpio:**
  - Nuevo botón **Cerrar sesión** siempre visible en **Ajustes** que limpia el progreso local desde cero y regresa a la pantalla inicial; si vuelves a elegir tu cuenta de Google, recuperas hasta el último progreso guardado en la nube.

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
