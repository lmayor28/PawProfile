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

**Mantenimiento:**

Monitorea el rendimiento y los comentarios de los usuarios. Realiza actualizaciones y mejoras continuas según sea necesario.

---

¡Espero que esto te ayude a darle un aspecto más profesional a tu README! ¿Algo más que necesites?
