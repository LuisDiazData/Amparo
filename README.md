# Amparo — Asistente financiero con IA (Android)


Amparo es un MVP de app Android que ayuda a las personas a manejar sus finanzas personales con IA: presupuesto inteligente, alertas, OCR de tickets y sincronización con facturas del SAT.


## 🧭 Roadmap (MVP)
- Registro/Login (Google o teléfono con SMS)
- Onboarding con explicación de valor
- Presupuesto inicial con sugerencias por IA
- Dashboard de metas, presupuesto y alertas
- Ingreso de gastos/ingresos (manual + OCR)
- Análisis y recomendaciones en tiempo real


## 🏗️ Arquitectura (alto nivel)
- **App Android:** Kotlin + Jetpack Compose + MVVM
- **IA/Servicios:** endpoints para presupuesto/alertas
- **Almacenamiento:** Room (local), API externa para OCR/SAT


> Ver `docs/architecture.md` para detalles.


## 🚀 Empezar
```bash
# Clonar y preparar
git clone https://github.com/<ORG_O_USER>/amparo.git
cd amparo


# Abrir en Android Studio y sincronizar Gradle