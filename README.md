<<<<<<< HEAD
# PawProfile

**Descripción:**

PawProfile es una innovadora aplicación móvil que permite a los dueños de mascotas crear y gestionar perfiles de sus amigos peludos. Los perfiles se vinculan a códigos QR que se pueden escanear para acceder a información esencial de la mascota.

**Características principales:**

- **Cuentas de usuario**: Autenticación con Firebase, posibilidad de iniciar sesión con email/contraseña o Google Sign-In.
- **Perfiles de mascotas**: Crear, editar y eliminar perfiles con información como nombre, raza, edad e imágenes.
- **Integración de códigos QR**: Escanea códigos QR para abrir perfiles en el navegador.
- **Notificaciones**: Envía la ubicación del usuario al dueño de la mascota a través de SMS con un enlace de Google Maps.
- **Estructura de navegación**: Botones de inicio, notificaciones y configuración para una navegación fácil.

**Tecnologías utilizadas:**

- **Frontend**: Flutter (cross-platform para iOS y Android)
- **Backend/Database**: Firebase para autenticación y almacenamiento en la nube
- **Servicios de terceros**: API de Google Maps

**Requisitos adicionales:**

- **Soporte de idioma**: Español como idioma predeterminado
- **Tablero de administración**: Dashboard básico para gestionar cuentas y datos de usuarios
- **Seguridad**: Protocolos básicos para la protección de datos de usuarios

**Despliegue:**

1. **Configuración del Proyecto:**
    ```sh
    flutter create petconnect
    cd petconnect
    ```

2. **Instalación de dependencias:**
    ```sh
    flutter pub add firebase_core firebase_auth cloud_firestore google_maps_flutter qr_code_scanner
    ```

3. **Configuración de Firebase:**
    - Agregar los archivos `google-services.json` y `GoogleService-Info.plist` a sus respectivas carpetas.
    - Configurar Firebase en tu proyecto Flutter.

4. **Ejecución de la Aplicación:**
    ```sh
    flutter run
    ```



### **Guía para Desarrollo de PawProfile**

---

1. **Definir objetivos y requisitos del proyecto**
   - Establecer los objetivos principales de la aplicación.
   - Identificar las características clave y los requisitos funcionales.

2. **Diseñar la estructura y el flujo de la aplicación**
   - Crear wireframes y prototipos básicos.
   - Diseñar la interfaz de usuario para las plataformas iOS y Android.

3. **Configurar el entorno de desarrollo**
   - Instalar Flutter y configurar el entorno de desarrollo.
   - Configurar Firebase para la autenticación y el almacenamiento en la nube.

4. **Desarrollar la interfaz de usuario (UI)**
   - Crear el diseño de la pantalla de inicio de sesión.
   - Diseñar las pantallas para la gestión de perfiles de mascotas y visualización de códigos QR.

5. **Implementar la autenticación de usuarios**
   - Configurar Firebase Authentication para registro y inicio de sesión.
   - Crear pantallas de inicio de sesión, registro y recuperación de contraseña.

6. **Desarrollar la gestión de perfiles de mascotas**
   - Implementar funciones para agregar, editar y eliminar perfiles de mascotas.
   - Permitir la carga de imágenes y almacenamiento en Firebase.

7. **Integrar la funcionalidad de códigos QR**
   - Añadir la funcionalidad de escaneo de códigos QR.
   - Implementar la lógica para abrir el perfil de la mascota en el navegador al escanear el código.

8. **Desarrollar la funcionalidad de notificación al dueño**
   - Crear el botón "Notificar al dueño" que abre la aplicación de SMS con un mensaje pre-llenado.
   - Usar la API de Google Maps para incluir la ubicación en el mensaje de SMS.

9. **Implementar notificaciones y alertas**
   - Configurar Firebase Cloud Messaging para enviar notificaciones estáticas a los dueños cuando se escanea un código QR.

10. **Diseñar la estructura de navegación**
    - Añadir botones de navegación en la parte inferior de la aplicación: Inicio, Notificaciones y Configuración.
    - Asegurar una navegación fluida y fácil de usar.

11. **Configurar el soporte de idioma**
    - Establecer el español como idioma predeterminado.

12. **Desarrollar el tablero de administración**
    - Crear un dashboard básico para gestionar cuentas y datos de usuarios.

13. **Implementar seguridad**
    - Configurar protocolos básicos de seguridad para la protección de datos de los usuarios.

14. **Realizar pruebas y depuración**
    - Realizar pruebas en dispositivos iOS y Android.
    - Solucionar errores y optimizar el rendimiento de la aplicación.

15. **Preparar el despliegue**
    - Preparar la aplicación para su lanzamiento en App Store y Google Play.
    - Cumplir con las guías y requisitos de publicación de la aplicación.

16. **Mantenimiento continuo**
    - Monitorear el rendimiento y los comentarios de los usuarios.
    - Realizar actualizaciones y mejoras continuas según sea necesario.

---



**Mantenimiento:**

Monitorea el rendimiento y los comentarios de los usuarios. Realiza actualizaciones y mejoras continuas según sea necesario.

---