**Unidad de Aprendizaje:** Desarrollo de aplicaciones móviles nativas  
**Institución:** Escuela Superior de Cómputo (ESCOM - IPN)  
**Alumno:** Jesús Ángel González Arellano  
**Boleta:** 2022630690 | **Grupo:** 7CV4  
**Profesor:** Gabriel Hurtado Avilés  

## Estructura del Repositorio
- `hola_mundo_xml/`: Aplicación Android nativa desarrollada con Views tradicionales en XML y Kotlin.
- `hola_mundo_compose/`: Aplicación Android nativa desarrollada con Jetpack Compose y diseño declarativo.
- `hola_mundo_flutter/`: Aplicación móvil multiplataforma desarrollada con Flutter y Dart.

## Instrucciones de Ejecución
1. **Views (XML):** Abrir en Android Studio la carpeta `hola_mundo_xml` y presionar Run (▶) o ejecutar `./gradlew installDebug`.
2. **Jetpack Compose:** Abrir en Android Studio la carpeta `hola_mundo_compose` y presionar Run (▶).
3. **Flutter:** Entrar a `hola_mundo_flutter` y ejecutar `flutter run`.

## Comparación Técnica de los Tres Enfoques
- **Views (XML):** Paradigma imperativo, separación estricta de vista (XML) y controlador (Kotlin). Mayor cantidad de código de enlace (ViewBinding / findViewById).
- **Jetpack Compose:** Paradigma declarativo en Kotlin nativo. Menor verbosidad, componentes modulares reutilizables y vista previa en tiempo real con `@Preview`.
- **Flutter:** Paradigma declarativo multiplataforma basado en árbol de widgets. Excelente velocidad de iteración gracias a Hot Reload y renderizado consistente en cualquier plataforma.
