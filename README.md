## María Teresa Rivera López
## 24000579

Lab06 Parte1-Parte2
La aplicación AI Chef es una app Android que utiliza inteligencia artificial para generar recetas de cocina de manera automática
a partir de ingredientes ingresados por el usuario. La aplicación muestra esta información en una interfaz desarrollada con 
Jetpack Compose, manejando estados de carga y posibles errores de conexión.

Además, la app permite compartir la receta como imagen, para ello:
Convierte el contenido visual de la receta en un archivo de imagen (Bitmap).
Guarda la imagen temporalmente en el almacenamiento interno.
Utiliza un FileProvider para generar una URI segura.

## Parte 1 – Recipe Favorites
- Configuración del proyecto con Firebase:
- Integración del proyecto Android con Firebase.
- Agregado del archivo google-services.json.
- Configuración de dependencias en Gradle.

Integración con Firebase AI Logic:
- Envío de prompt dinámico con ingredientes ingresados por el usuario.
  Recepción de respuesta estructurada desde la IA.
  Generación automática de:
  - Título de receta
  - Lista de ingredientes
  - Instrucciones
  - Imagen generada

Carga de imagen generada:
Uso de Coil para renderizar la imagen retornada por la IA.
Manejo seguro de errores al cargar imágenes.
Uso de clases de datos para modelar la receta.


## Parte 2 – Recipe Sharing
- Conversión de Composable a Bitmap
- Implementación de ShareUtils:
  Creación del archivo util/ShareUtils.kt.

- Configuración de FileProvider:
  Declaración en AndroidManifest.xml.
  Creación del archivo res/xml/file_paths.xml.
  Generación de URI segura para compartir archivos.


Link del video: https://youtu.be/wr11pOG8-m4

El documento que genero Firestore en donde de encuentra la API key no fue commiteado.


Con ayuda de IA pude agilizar parte del proyecto y la documentacion, asi como comprender mejor el funcionamiento de Android, el funcionamiento 
y aplicacion de las API key para el laboratorio al igual que su estructura al hacer una app y en que carpetas colocarlas.
