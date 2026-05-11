# 📱 FichaDirecta - Mobile App

![Flutter](https://img.shields.io/badge/Flutter-3.19-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.3-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Riverpod](https://img.shields.io/badge/State_Management-Riverpod-4DB6AC?style=for-the-badge)
![UI/UX](https://img.shields.io/badge/UI/UX-Dark_Mode-00E676?style=for-the-badge)

La aplicación móvil de **FichaDirecta** es el puente entre el talento del fútbol base y los clubes profesionales. Una experiencia nativa diseñada para el scouting moderno, rápida y visualmente impactante.

---

## 🚀 Características Principales

*   **⚡ Interfaz de Alto Rendimiento:** Animaciones fluidas y transiciones optimizadas para una experiencia premium.
*   **🎥 Reproductor Multimedia:** Visualización de vídeos de presentación con carga inteligente y gestión de miniaturas.
*   **🧩 Arquitectura Modular:** Separación por *features* para facilitar la escalabilidad y el mantenimiento.
*   **💎 Diseño Visual (Neon Dark):** Estética moderna basada en contrastes de verde neón sobre fondos oscuros, siguiendo tendencias de apps deportivas de élite.
*   **🛠️ Gestión de Estado:** Implementación robusta con **Riverpod** para un flujo de datos predecible y reactivo.

---

## 🎨 Sistema de Diseño

Nuestra identidad visual refleja la energía del fútbol y la precisión de la tecnología:

*   **Primary Color:** `#00E676` (Neon Green) - Simboliza el césped bajo los focos.
*   **Background:** `#0A0A0A` (Deep Dark) - Para máxima legibilidad y ahorro de batería (AMOLED).
*   **Typography:** `Outfit` / `Inter` - Fuentes modernas y deportivas.
*   **Components:** Glassmorphism, gradientes suaves y micro-interacciones.

---

## 📂 Estructura del Proyecto

Seguimos una estructura orientada a dominios (*Feature-first*):

```text
lib/
├── core/               # Configuración global, temas, API Client y rutas.
├── shared/             # Widgets y componentes comunes (botones, cards).
├── features/           # Módulos independientes por funcionalidad:
│   ├── auth/           # Login, Registro y validación JWT.
│   ├── onboarding/     # Selección de rol (Jugador/Club).
│   ├── profile/        # Gestión de datos, fotos y vídeos (Cloudinary).
│   └── feed/           # Búsqueda de talento y vacantes.
└── main.dart           # Inicialización de la app y Providers.

© 2026 FichaDirecta - El fútbol base, digitalizado.
