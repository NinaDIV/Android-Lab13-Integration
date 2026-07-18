# Laboratorio Android 13 — Integración de APIs REST con Retrofit

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Retrofit](https://img.shields.io/badge/Retrofit-48B983?style=flat&logoColor=white)

Laboratorio Android N.º 13 sobre integración de APIs externas y consumo de servicios REST con Retrofit. Cubre el manejo asíncrono de datos con Coroutines, la serialización JSON y la actualización de la UI con los resultados de red.

## 📚 Temas cubiertos

- Cliente HTTP con Retrofit 2
- Serialización JSON con Gson o Moshi
- Coroutines para llamadas asíncronas
- Manejo de estados: loading, success, error
- RecyclerView con datos de la API

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| Kotlin | Lenguaje principal |
| Android SDK | Plataforma de desarrollo |
| Retrofit 2 | Cliente HTTP para consumir la API REST |
| Gson / Moshi | Serialización y deserialización JSON |
| Coroutines | Llamadas asíncronas a la red |
| RecyclerView | Listado de datos obtenidos de la API |

## ✅ Requisitos previos

Antes de ejecutar el proyecto necesitas tener instalado:

- **Android Studio** (versión reciente recomendada)
- **JDK 17** (incluido con las versiones actuales de Android Studio)
- **Android SDK** con las Platform Tools actualizadas
- **Emulador de Android** configurado en AVD Manager, o un **dispositivo físico** con la depuración USB activada
- **Conexión a internet** en el emulador/dispositivo (el laboratorio consume una API REST)

## 🚀 Instalación y ejecución

1. Clona el repositorio:

   ```bash
   git clone https://github.com/NinaDIV/Android-Lab13-Integration.git
   cd Android-Lab13-Integration
   ```

2. Abre Android Studio y selecciona **Open**, apuntando a la carpeta del proyecto que quieras trabajar (el laboratorio principal está en `LAB/`; los codelabs son proyectos independientes).

3. Espera a que Gradle sincronice las dependencias (la primera vez puede tardar unos minutos).

4. Selecciona un emulador o dispositivo físico y presiona **Run** (▶).

5. Al arrancar, la app realiza las llamadas a la API REST y muestra los datos en un listado (`RecyclerView`), pasando por los estados de carga, éxito o error según la respuesta de red.

## 📁 Estructura del proyecto

El repositorio agrupa el laboratorio junto con los codelabs oficiales de Jetpack Compose usados como material de práctica:

```
Android-Lab13-Integration/
├── LAB/                                  # Laboratorio 13: integración de APIs REST
├── AdaptiveUiCodelab/                    # Codelab de UI adaptativa
├── AdvancedStateAndSideEffectsCodelab/   # Codelab de estado avanzado y side effects
├── AnimationCodelab/                     # Codelab de animaciones
├── BasicLayoutsCodelab/                  # Codelab de layouts básicos
├── BasicStateCodelab/                    # Codelab de estado básico
├── BasicsCodelab/                        # Codelab de fundamentos de Compose
├── NavigationCodelab/                    # Codelab de navegación
├── PerformanceCodelab/                   # Codelab de rendimiento
├── scripts/                              # Scripts auxiliares
└── README.md
```

Cada carpeta es un proyecto de Android Studio independiente con su propio Gradle Wrapper (`gradlew`).
