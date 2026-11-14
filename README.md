# Aurea Releases 🚀

Canal oficial y público de distribución y actualización continua para **Aurea: Tu Santuario de Enfoque y Éxito Académico**.

---

## 📥 Descarga Directa de la Última Versión

- **Última Versión:** `v0.2.1` (Build `29`)
- **Descargar APK Oficial:** [Aurea.apk](https://raw.githubusercontent.com/angelhuamactomerino/aurea-releases/main/apk/Aurea.apk)
- **Manifiesto de Versión:** [version.json](https://raw.githubusercontent.com/angelhuamactomerino/aurea-releases/main/version.json)

---

## ✨ Novedades hasta v0.2.1 (Build 29)

- **Autenticación Firebase y Sincronización en la Nube:**
  - Registro y autenticación directa con Google (Credential Manager) y Correo/Contraseña en Firebase Authentication (`aurea-10d05`), eliminando fallbacks locales silenciosos.
  - Diagnóstico interactivo de Firebase con copia rápida de la huella `SHA-1` de producción (`5E:7D:E3:98:F8:B4:DA:6E:6D:F4:E6:57:3C:60:1B:C8:63:F7:7C:52`).
  - Sincronización bidireccional en Cloud Firestore (`users/{uid}`) basada en `syncId` (UUID), marcas temporales `updatedAtEpoch` y escritura por lotes.
- **Formicarium Subterráneo en Vivo y Mirmecofauna del Perú:**
  - Catálogo ampliado a **43 especies nativas del Perú agrupadas en 14 géneros** (incluyendo expansiones recientes de *Camponotus* y *Pheidole*), con hibernación segura de colonias secundarias, regla de 30 días para cambio de colonia principal y morfologías/skins en Canvas.
  - Cámaras iluminadas interactivas, Pomodoro circular tolerante a reinicios, racha diaria con escudos (*Streak Freezes*), misiones, eventos 24h, tienda subterránea y jefes semanales.
- **Tema Adaptativo y Protección Monotónica (`MonotonicClockGuard`):**
  - 4 modos visuales reactivos (**Sistema**, **Claro**, **Dark Slate** y **Midnight OLED**) con 4 paletas de acento (*Teal*, *Índigo*, *Ámbar* y *Violeta*).
  - Sesiones Búnker, Pomodoro y reglas ancladas a `elapsedRealtime` y `BOOT_COUNT`, más servicio bajo demanda (`FocusMonitorService`) y Room Schema v10 con migraciones incrementales `1..10`.
- **Módulo Académico, Horarios y Acompañantes Universales (1:1):**
  - Ciclos semestrales, cursos con créditos, grupos de evaluaciones con modos de redondeo y promedio ponderado/simple.
  - **Charlote** (26 pistas de voz 1:1 y retratos dinámicos) y sistema universal de acompañantes importables/exportables en `.zip`.

---

## 🔄 Actualización In-App

La aplicación Aurea consulta automáticamente este repositorio público (`version.json`) para verificar si existe una nueva compilación (`manifest.versionCode > BuildConfig.VERSION_CODE`) y descargar el APK firmado directamente en el dispositivo sin necesidad de tokens o credenciales privadas de GitHub.

> [!NOTE]
> **Respaldo en Google Drive:** Siempre que se actualice este repositorio en GitHub, la versión correspondiente también se actualizará en **Google Drive > `Proyectos` > `Aurea`**.
