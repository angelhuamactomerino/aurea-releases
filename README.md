# Aurea Releases 🚀

Canal oficial y público de distribución y actualización continua para **Aurea: Tu Santuario de Enfoque y Éxito Académico**.

---

## 📥 Descarga Directa de la Última Versión

- **Última Versión (Fase Beta):** `v0.0.1 (Beta)` (Build `17`)
- **Descargar APK Oficial:** [Aurea.apk](https://raw.githubusercontent.com/angelhuamactomerino/aurea-releases/main/apk/Aurea.apk)
- **Manifiesto de Versión:** [version.json](https://raw.githubusercontent.com/angelhuamactomerino/aurea-releases/main/version.json)

---

## 🌟 Novedades en v0.0.1 (Fase Beta)

- **Identificación Oficial en Fase Beta (v0.0.1):** Versionado sincronizado en toda la aplicación y pantalla principal.
- **Selector de Evaluación Individual vs. Conjunto / Grupo:**
  - **Individual:** Para parciales, finales o proyectos únicos con su propio peso porcentual (ej. Parcial 30%, Final 40%).
  - **Conjunto / Grupo:** Para conjuntos de evaluaciones promediadas (ej. 7 Prácticas Calificadas que en conjunto valen 30%).
- **3 Políticas de Redondeo para Promedios de Grupos:**
  - 🔢 **Mantener en decimales (`DECIMAL`):** Conserva el promedio exacto con decimales (ej. 10.50 se mantiene en 10.50).
  - ⚖️ **Redondeo estándar (`STANDARD_ROUND`):** Medio punto a favor: 10.5 o más sube a 11 (10.8 sube a 11), menor a 10.5 trunca a 10 (10.4 baja a 10).
  - 📉 **Redondear al más bajo / Piso (`FLOOR`):** Siempre trunca hacia abajo al entero inferior (incluso 10.8 o 10.5 pasa a ser 10).
- **Interfaz Académica Rediseñada y Amigable:**
  - Tarjetas visuales de conjunto con badges de regla de redondeo (`.5 a favor`, `Piso`, `Decimales`).
  - Botón de ajuste rápido de conjunto (ícono de sintonizador) para modificar peso y regla de redondeo en cualquier momento.
  - Creación masiva rápida de evaluaciones en grupo (generador con selector 1 a 15 evaluaciones).
  - Indicadores de meta y consejos predictivos para aprobar sin estrés.

---

## 🔄 Actualización In-App

La aplicación Aurea consulta automáticamente este repositorio público para verificar si existe una nueva compilación disponible y descargarla directamente en el dispositivo sin necesidad de tokens o credenciales privadas de GitHub.
