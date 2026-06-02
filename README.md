# <p align="center" width="100%"> ![Birthday](https://user-images.githubusercontent.com/73078636/193473544-ae5d7636-6bf5-4313-91cf-f5d627d31c72.png)</p>
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
 
  
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)  ![first-timers-only](https://img.shields.io/badge/first--timers--only-friendly-yellow.svg?style=flat) ![contributions welcome](https://img.shields.io/static/v1.svg?label=Contributions&message=Welcome&color=0059b3&style=flat-square)
</p>
A beginner friendly project to help you in open source contributions. An attempt to bring Web Projects together.


**Please see the <a href="https://github.com/Anadee11/WebArena/blob/main/CONTRIBUTING.md"> **Contributing Guidelines** </a>.**


## Overview

The goal of this project is to help the beginners with their contributions in Open Source and to bring all the Web projects together. We aim to achieve this collaboratively, so feel free to contribute in any way you want, just make sure to follow the contribution guidelines.


## What is Open - Source? [![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
The open source community provides a great opportunity for aspiring programmers to distinguish themselves; and by contributing to various projects, developers can improve their skills and get inspiration and support from like-minded people. When you contribute to something you already know and love, it can have so much more meaning, because you know how the tool is used and the good it does for you. Being part of an open source community opens you up to a broader range of people to interact with. 

Read more about it <a href="https://www.digitalocean.com/community/tutorial_series/an-introduction-to-open-source"> here. </a>


## <u> Let's Get Started: </u>

### Issue Creation
- Create an issue or if you want to work on an exisiting issue get it assigned to you first.
- **No PR's shall be accepted without issues been assigned.**
- Now, when you have got your issue assigned follow the steps below :



### Step 1. Create a Copy of this Repository
In order to work on an open-source project, you will first need to make your own copy of the repository. To do this, you should fork the repository and then clone it so that you have a local working copy.

> **Fork :fork_and_knife: this repo. Click on the Fork button at the top right corner.**

With the repository forked, you’re ready to clone it so that you have a local working copy of the code base.

> **Clone the Repository**

To make your own local copy of the repository you would like to contribute to, let’s first open up a terminal window.

We’ll use the git clone command along with the URL that points to your fork of the repository.

* Open the Command Prompt
* Type this command:

```
git clone https://github.com/your_username/WebArena
```

<kbd><img width="633" alt="Screenshot 2022-10-04 at 2 53 53 AM" src="https://user-images.githubusercontent.com/73078636/193685501-b92510c3-2b9d-401c-abe0-834b4fdfccab.png"></kbd>



### Step 2: Creating a New Branch
It is important to branch the repository so that you are able to manage the workflow, isolate your code, and control what features make it back to the main branch of the project repository.

When creating a branch, it is very important that you create your new branch off of the master branch. 
**To create a new branch, from your terminal window, follow:**


```
git branch new-branch
git checkout new-branch
```
Once you enter the git checkout command, you will receive the following output:

```
Switched to branch 'new-branch'
```


### Step 3: Contribute
- Make relevant changes.Add new projects(make sure to put in the readme files in your folders). 
- Contribute with any web project you feel like :)

### Step 4: Commiting and Pushing:
Once you have modified an existing file or added a new file to the project, you can add it to your local repository, which we can do with the git add command.

``` git add filename``` or ``` git add .``` 

You can type the command ```git add -A``` or alternatively ```git add -all``` for all new files to be staged.


**With our file staged, we’ll want to record the changes that we made to the repository with the ```git commit``` command.**
<p> The commit message is an important aspect of your code contribution; it helps the other contributors fully understand the change you have made, why you made it, and how significant it is.  </p>
 
 ```
 git commit -m "commit message"
 ```
 
 
 At this point you can use the ```git push``` command to push the changes to the current branch of your forked repository:
 ```
 git push --set-upstream origin new-branch
 ```
 
### Step 6: Create Pull Request
At this point, you are ready to make a pull request to the original repository.

You should navigate to your **forked** repository, and press the “Compare & pull request” button on the page. 
<kbd><img width="911" alt="Screenshot 2022-10-04 at 3 21 21 AM" src="https://user-images.githubusercontent.com/73078636/193692534-54eb66df-9f17-40fc-accd-deca18f802fd.png"></kbd>

GitHub will alert you that you are able to merge the two branches because there is no competing code. You should add in a **title**, a **comment**, and then press the **“Create pull request”** button.

<kbd>
  <img width="912" alt="Screenshot 2022-10-04 at 3 24 21 AM" src="https://user-images.githubusercontent.com/73078636/193692962-69677f51-c1ec-4ee8-b123-012de4411434.png">
</kbd>

### Step 7: CONGRATULATIONS :boom: :clap: :relaxed:
You have made it till the end. Kudos to you!!

<hr> </hr>

### How to upload the files

* Upload your folders with the corresponding files and a readme.md file.
* **Under no circumstances create new folders or directly upload files within the folders of other projects.**

#### Please see the <a href="https://github.com/Anadee11/WebArena/blob/main/CONTRIBUTING.md"> **Contributing Guidelines** </a>.

<hr> </hr>

## Please STAR :star2: this repository if you liked it and had fun :)

### Maintainer! :blush:

<table>
  <tbody><tr>
    <td align="center"><a href="https://github.com/anadee11"><img alt="" src="https://avatars.githubusercontent.com/anadee11" width="100px;"><br><sub><b>Anadee</b></sub></a><br><a href="https://github.com/anadee11" title="Code">💻 🖋</a></td> </a></td>
  </tr>
</tbody></table>
<hr>

# Student Contribution

## Developer Information

- Name: Juan Gustavo Ángel Cruz Méndez
- University: Universidad Tecnológica del Norte de Guanajuato
- Date: 01/06/2026

## Proposed Improvements

1. **Automatización del Inicio del Servicio**: Configurar el servicio de MySQL (ya sea mediante Servicios de Windows, XAMPP o Laragon) para que se inicie automáticamente con el sistema. Esto garantiza que el motor de la base de datos esté disponible siempre que se abra el IDE, evitando errores de conexión fallida.
2. **Política de Gestión de Credenciales**: Utilizar la función "Store in Vault" para entornos de desarrollo local para agilizar el flujo de trabajo. Para entornos de producción, implementar una política de entrada manual o mediante variables de entorno para mejorar la seguridad.
3. **Aislamiento de Entornos**: Organizar las conexiones utilizando la función de grupos de MySQL Workbench y aplicar códigos de colores distintos (por ejemplo, verde para local, rojo para producción) para minimizar el riesgo de modificaciones accidentales en entornos equivocados.

## Observations

La fase de configuración inicial reveló que el fallo principal de conexión fue causado por la ausencia de un motor de base de datos activo, confirmando que **MySQL Workbench** opera estrictamente como una interfaz de cliente. Los errores posteriores de "Acceso Denegado" resaltaron la importancia de distinguir entre las configuraciones de credenciales predeterminadas (como la política de contraseña vacía en XAMPP/Laragon) y los requisitos obligatorios de contraseña del instalador oficial de MySQL Server. Las pruebas finales confirmaron que, una vez que el servicio está activo en el puerto `3306` con las credenciales correspondientes, la conexión se mantiene estable.

## Project Strengths

* **Enfoque Arquitectónico Sólido (MVVM & API-First):** La adopción del patrón de diseño *Model-View-ViewModel* (estándar oficial de Google para Android) garantiza una clara separación de responsabilidades entre la lógica de negocio y la interfaz de usuario, facilitando la escalabilidad, la mantenibilidad y las pruebas unitarias. Al ser una arquitectura API-first, desacopla de forma eficiente el cliente móvil del backend, permitiendo la futura expansión hacia otras plataformas del ecosistema (Wearables, Smart TV, etc.).
* **Gestión Eficiente de Red e Infraestructura de Consumo:** La integración de **Retrofit** para el consumo de la API REST proporciona un tipado estricto y una gestión óptima de las peticiones HTTP, complementada con el requisito obligatorio de seguridad mediante tokens de acceso **JWT** y cifrado **HTTPS** para mitigar ataques de interceptación (MitM).
* **Inclusión de Streaming de Video de Alta Calidad:** La incorporación del protocolo **HLS Adaptativo (HTTP Live Streaming)** operado a través de **ExoPlayer** demuestra un diseño moderno y pensado en la experiencia de usuario, adaptando la resolución del contenido audiovisual automáticamente en función del ancho de banda disponible del dispositivo móvil.
* **Estrategia de Preservación e Interactividad Cultural:** A diferencia de las aplicaciones convencionales de eventos que solo venden boletos, FestivalTrack aporta un valor agregado diferenciador mediante la implementación de un *Fragment* de Biografía Interactiva enfocado en el impacto histórico y cultural de José Alfredo Jiménez (multimedia con galerías y reproductores de audio nativos con tiempos de carga optimizados menores a 3 segundos).
* **Seguridad y Control de Acceso mediante Códigos QR:** La automatización de la venta de boletos asociada a la generación dinámica de un Token visual (Código QR) proporciona un mecanismo robusto, transparente y ágil tanto para el usuario como para el personal del festival en los controles de acceso físicos del recinto (Mausoleo).

---

## Improvement Opportunities

* **Definición de Almacenamiento Local (Persistencia Caching):** El documento menciona resiliencia del backend y reconexión automática ante la pérdida de señal, pero no define formalmente una base de datos local embebida en el cliente Android (como **Room SQL** o **DataStore**). Es crítico estructurar una estrategia *Offline-First* para que los usuarios puedan consultar sus boletos (códigos QR) y la agenda previamente descargada cuando se encuentren en áreas de alta densidad o nula conectividad en el festival.
* **Transición y Unificación del Stack Tecnológico de UI:** El glosario y las descripciones mencionan la coexistencia de `Activity`, `Fragment` y la combinación de lenguajes `Kotlin / Java`. Se recomienda encarecidamente migrar y unificar el desarrollo hacia **Jetpack Compose** (desarrollo declarativo de UI moderno) y usar exclusivamente Kotlin para eliminar el código heredado, evitar la sobrecarga de inflar vistas XML y reducir la complejidad del ciclo de vida que implican los Fragments tradicionales.
* **Detalle en la Escalabilidad y Robustez del Panel de Administración:** La HU-05 establece que el administrador puede subir archivos multimedia directamente desde la app móvil. Esto puede generar cuellos de botella en dispositivos móviles debido al ancho de banda de subida. Una mejor práctica sería delimitar el Panel de Administración como una plataforma web independiente o especificar librerías de compresión/procesamiento asíncrono en segundo plano (**WorkManager**) dentro de la aplicación móvil.
* **Especificación de la Pasarela de Pagos:** La HU-02 detalla que los boletos se adquieren mediante una "pasarela segura", pero no detalla el proveedor técnico (e.g., Stripe SDK, PayPal SDK o Mercado Pago SDK). Definir formalmente los requerimientos de cumplimiento (PCI-DSS) y las librerías específicas evitará complicaciones en etapas avanzadas de desarrollo.
* **Estrategia Exhaustiva de Pruebas (Testing):** No se visualizan requerimientos o arquitecturas destinadas a la verificación de software. Se sugiere incorporar al alcance arquitectónico la definición de pruebas unitarias (JUnit, Mockk) para los ViewModels y casos de uso, así como pruebas de interfaz de usuario automatizadas (Espresso) para los flujos críticos de autenticación y checkout de boletos.

## 3. Tabla de Tecnologías Utilizadas

A continuación se consolidan las herramientas, lenguajes, protocolos y librerías clave que componen el ecosistema de **FestivalTrack** según la documentación técnica provista:

| Componente / Capa | Tecnología | Tipo / Propósito | Descripción Técnica |
| :--- | :--- | :--- | :--- |
| **Entorno de Desarrollo** | Android Studio | IDE Oficial | Entorno de desarrollo integrado para la codificación y emulación del sistema Android. |
| **Lenguajes de Programación**| Kotlin / Java | Lenguajes de Software | Stack mixto nativo para la estructuración de la lógica de negocio y componentes de UI. |
| **Arquitectura de Software** | MVVM | Patrón Arquitectónico | *Model-View-ViewModel* para separación de vistas, flujos de datos reactivos y lógica. |
| **Consumo de APIs** | Retrofit | Librería HTTP Client | Cliente seguro de tipo *Type-safe* para interactuar con los endpoints del backend REST. |
| **Reproducción de Video** | ExoPlayer / HLS | Reproductor Multimedia | API multimedia nativa compatible con streaming adaptivo basado en el ancho de banda. |
| **Autenticación** | JWT (JSON Web Tokens) | Protocolo de Seguridad | Tokens firmados digitalmente para la persistencia e identificación segura de sesiones. |
| **Cifrado de Red** | HTTPS | Protocolo de Red | Capa de sockets seguros encargada de encriptar el tráfico de datos cliente-servidor. |
| **Validación Física** | Código QR | Token Visual | Matriz de puntos bidimensional para verificación automatizada en accesos del evento. |

---

## 4. Diagrama de Arquitectura
---

### 🏛️ 7. Arquitectura del Sistema (MVVM & Clean Architecture)

El siguiente flujo describe la arquitectura limpia implementada bajo el patrón MVVM y el flujo de comunicación asíncrona para el consumo de servicios web externos en la aplicación Android:

```text
+---------------------------------------------------------------------------------+
|                                APLICACIÓN ANDROID                               |
|                                                                                 |
|  +--------------------------- Capa de Presentación --------------------------+  |
|  |                                                                           |  |
|  |   [ Vistas Nativas ] <--- (Observa Estado / Data Binding) ------------+   |  |
|  |   (Activities / Fragments / Compose UI)                               |   |  |
|  |                                                                       |   |  |
|  +-----------------------------------------------------------------------|---+  |
|                                                                          v      |
|  +--------------------------- Capa de Negocio -------------------------------+  |
|  |                                                                           |  |
|  |   [ ViewModels ]                                                          |  |
|  |   (Maneja el estado de la UI y los eventos del usuario)                   |  |
|  |                                                                           |  |
|  |   [ Repository Pattern ]                                                  |  |
|  |   (Abstracción y decisión de la fuente de datos: Local o Remota)          |  |
|  |                                                                           |  |
|  +-----------------------------------------------------------------------|---+  |
|                                                                          v      |
|  +--------------------------- Capa de Datos ---------------------------------+  |
|  |                                                                           |  |
|  |   [ Retrofit API Client ] ----(Mapeo de Datos DTO)                     |  |
|  |                                                                           |  |
|  +-------------------------------------+-------------------------------------+  |
+----------------------------------------|----------------------------------------+
                                         |
                                   (HTTPS / JWT)
                                         v
+---------------------------------------------------------------------------------+
|                             SERVICIOS EXTERNOS / BACKEND                        |
|                                                                                 |
|   +-----------------------+   +------------------------+   +----------------+   |
|   |   API Gateway REST    |   | HLS Video Server (CDN) |   | Pasarela Pago  |   |
|   |   (Endpoints Backend) |   | (Streaming ExoPlayer)  |   | (Tokenización) |   |
|   +-----------------------+   +------------------------+   +----------------+   |
+---------------------------------------------------------------------------------+
```
---

## 5. Requerimientos Funcionales (10 Requerimientos)

Los requerimientos funcionales detallan el comportamiento específico que el sistema debe ejecutar de manera explícita:

* **RF-01 (Gestión de Cuentas):** El sistema debe permitir a los visitantes registrar una cuenta nueva mediante un correo electrónico válido y una contraseña con criterios mínimos de seguridad.
* **RF-02 (Inicio de Sesión):** El sistema debe validar las credenciales de los usuarios mediante tokens JWT a través de HTTPS para otorgar acceso a las funciones extendidas de la aplicación.
* **RF-03 (Búsqueda y Compra de Boletos):** El sistema debe permitir al usuario seleccionar una fecha del festival, una categoría de asiento, la cantidad de boletos y procesar el pago a través de la pasarela integrada.
* **RF-04 (Generación de Códigos QR):** Tras una transacción bancaria exitosa, el sistema debe generar automáticamente un boleto electrónico en formato de código QR único vinculado a la cuenta del usuario.
* **RF-05 (Consulta de Agenda/Horarios):** El sistema debe desplegar un listado cronológico interactivo que muestre los horarios de las presentaciones, artistas invitados y ubicaciones exactas de los escenarios (e.g., Mausoleo).
* **RF-06 (Streaming en Vivo):** El sistema debe reproducir la señal streaming de video en directo del festival mediante ExoPlayer consumiendo el protocolo HLS, garantizando calidad dinámica según la red del usuario.
* **RF-07 (Navegación Biográfica Interactiva):** El sistema debe renderizar una línea de tiempo interactiva que incluya textos históricos, galerías de imágenes y controles de reproducción para archivos de audio dedicados al legado de José Alfredo Jiménez.
* **RF-08 (Carga de Archivos de Administrador):** El sistema debe proveer una interfaz exclusiva para cuentas con rol de administrador que les permita cargar archivos de música, fotografías y textos informativos directamente al servidor de contenidos.
* **RF-09 (Notificaciones Push en Tiempo Real):** El sistema debe emitir alertas instantáneas a los dispositivos de los usuarios informando sobre cambios repentinos en la programación, eventos por comenzar o avisos de protección civil.
* **RF-10 (Historial de Compras Digitales):** El sistema debe almacenar y desplegar un módulo de consulta privada donde el usuario visualice sus transacciones pasadas, estado de pagos y boletos activos o expirados.

## 📁 6. Evidencias del Proceso

A continuación, se detallan las capturas de pantalla que validan el flujo de trabajo realizado en el proyecto **WebArena**.

---

###  Configuración del Repositorio
**Captura del Fork creado**  
Se realizó la bifurcación del repositorio base para iniciar el entorno de desarrollo personalizado.

<p align="center">
  <img src="https://github.com/user-attachments/assets/f8cd0a94-ce5a-4193-9d45-51cc1968d2e7" alt="Fork del repositorio" width="90%">
</p>

---

### 💻 Operaciones en Terminal (Git CLI)

> [!IMPORTANT]
> Se verificó la conexión con los repositorios remotos (`origin` y `upstream`) y la gestión de ramas locales.

#### **I. Configuración de Remotos (`git remote -v`)**
<img src="https://github.com/user-attachments/assets/2d1527d2-828a-4f5e-84aa-a5c40094be7a" alt="Git Remote" width="80%">

#### **II. Estado de Ramas (`git branch`)**
<img src="https://github.com/user-attachments/assets/54768a8d-f327-407a-902f-5584f76e46ae" alt="Git Branch" width="80%">

#### **III. Historial de Cambios (`git log --oneline`)**
<img src="https://github.com/user-attachments/assets/b9defeb9-c62a-4388-8211-f6111df3fbaa" alt="Git Log" width="90%">

---

### 🚀 Colaboración y Entrega (Pull Request)

**Captura del Pull Request**  
Evidencia del envío de contribuciones desde la rama `dev` hacia el repositorio principal.

<img src="https://github.com/user-attachments/assets/e63c0fcd-30b9-49b0-85d0-9031446d597e" alt="Pull Request Screenshot" width="100%">

**Enlace de seguimiento:**  
🔗 [Consultar Pull Request en GitHub](https://github.com/gusmendez3249/WebArena/pull/1#issue-4567640241)

---

## 👥 Team Members

| Nombre Completo | Rol / Responsabilidad |
| :--- | :--- |
| **Chavero Martínez Noe** | Ingeniero de Software |
| **Cruz Méndez Juan Gustavo** | Ingeniero de Software |
| **Salinas Salinas Omar** | Ingeniero de Software |

---
