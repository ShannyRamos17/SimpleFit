# [SimpleFit]

> **Proyecto Integrador - Desarrollo de Aplicaciones Móviles**
>
> **Semestre:** [4 - E]
> **Fecha de entrega:** 11 de Diciembre

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## Equipo de Desarrollo

| Nombre Completo          | Rol / Tareas Principales | Usuario GitHub |
|Leonardo Diaz Espinosa    | Backend, Logica	      |LeonardoDiazz   |
|Murat Castro Alvarez      | Repositorio, Design      |  Murat_rat     |
|Shanny Ramos Santiesteban | *********                |ShannyRamos17   |


--------------------------------------------------------------------------------------------------------------------------------------------------------
## Descripción del Proyecto

**¿Qué hace la aplicación?**
Esta aplicación es un rastreador de actividad física enfocado en corredores y caminantes. Permite al usuario registrar, guardar y gestionar sus sesiones de entrenamiento. Su funcionalidad principal es el uso del Acelerómetro del dispositivo para detectar el movimiento (pasos), y mediante algoritmos internos, calcular estadísticas clave como la distancia recorrida, la velocidad promedio y el tiempo total de la actividad, sin depender exclusivamente del GPS.

**Objetivo:**
Demostrar la implementación de una arquitectura robusta en Android utilizando servicios web (API REST) para el almacenamiento de datos en la nube y el hardware del dispositivo (sensores) para la captura de datos físicos en tiempo real.

-------------------------------------------------------------------------------------------------------------------------------------------------------------

## Stack Tecnológico y Características

Este proyecto ha sido desarrollado siguiendo estrictamente los lineamientos de la materia:

* **Lenguaje:** Kotlin 100%.
* **Interfaz de Usuario:** Jetpack Compose.
* **Arquitectura:** MVVM (Model-View-ViewModel).
* **Conectividad (API REST):** Retrofit.
* **GET:** Obtiene el historial de actividades ("Mis Recorridos" y "Recorridos Globales"), recuperando datos como: usuario, tiempo cronometrado, distancia recorrida, 	velocidad promedio y fecha de modificación.
* **POST:** Crea un nuevo registro en la base de datos al presionar "Detener recorrido", enviando las estadísticas finales calculadas durante la sesión.
* **UPDATE:** Permite actualizar la información de un recorrido existente (reflejado en el campo "Última Modificación" visible en las tarjetas).
* **DELETE:** Elimina permanentemente un recorrido seleccionado mediante el botón de "Borrar" y su posterior confirmación en el cuadro de diálogo.
* **Sensor Integrado:** Acelerómetro.
* *Uso:* Funciona como podómetro en tiempo real. Detecta la oscilación del dispositivo al correr o caminar para contabilizar pasos, los cuales se procesan mediante un algoritmo para calcular la **distancia** y la **velocidad promedio** que se muestran en la pantalla de progreso.

--------------------------------------------------------------------------------------------------------------------------------------------------------------

## Capturas de Pantalla

[Coloca al menos 3 (investiga como agregarlas y se vean en GitHub)]

| Pantalla de Inicio | Operación CRUD | Uso del Sensor |
| :---: | :---: | :---: |
| ![Inicio](url_imagen) | ![CRUD](url_imagen) | ![Sensor](url_imagen) |

---------------------------------------------------------------------------------------------------------------------------------------------------

## Instalación y Releases

El ejecutable firmado (.apk) se encuentra disponible en la sección de **Releases** de este repositorio.

[Liga correctamente tu link de releases en la siguiente sección]

1.  Ve a la sección "Releases" (o haz clic [aquí](link_a_tus_releases)).
2.  Descarga el archivo `.apk` de la última versión.
3.  Instálalo en tu dispositivo Android (asegúrate de permitir la instalación de orígenes desconocidos).
