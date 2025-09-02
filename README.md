# Evaluación 1

## Parte 2.

### Paso 1 - Configuración base:
- Crear y activar entorno virtual.
- Instalar Django.
![Creación y activación de entorno virtual; instalación de Django](images/1.png)

- Crear proyecto y aplicación.
![Proyecto y aplicación](images/2.png)

- Registrar la aplicación en el proyecto, y otras configuraciones.

    - En la lista INSTALLED_APPS agregar la app.
    ![INSTALLED_APPS](images/3.png)

    - Cambiar LANGUAGE_CODE = 'en-us' por LANGUAGE_CODE = 'es-cl'.
    - Cambiar TIME_ZONE = 'UTC' por TIME_ZONE = 'America/Santiago'.
    ![LANGUAGE_CODE & TIME_ZONE](images/4.png)

    - Generar la carpeta templates; cambiar 'DIRS': [], por 'DIRS': [BASE_DIR / 'templates'].
    ![DIRS](images/5.png)

    - Ejecutar el servidor de desarrollo.
    ![Servidor](images/6.png)

### Paso 2 - Definición de rutas:
- reservas/urls.py:
![reservas/urls](images/7.png)

- restaurante/urls.py:
![reservas/urls](images/8.png)

## Parte 3.

### Paso 1 - Definir modelos:
### Paso 2 - Migraciones:
![Modelo y migraciones](images/9.png)

## Interfaz de Usuario (UI):
![](images/10.png)

![](images/11.png)

![](images/12.png)
