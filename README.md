# Microservicio `ms-login-manager`

## Introducción
`ms-login-manager` es un microservicio desarrollado en .NET 7, diseñado para gestionar la validación de usuarios y el acceso a la aplicación. Proporciona una capa eficiente y segura para las operaciones relacionadas con la autenticación.

## Requisitos
- .NET 7 SDK
- PostgreSQL


## Modelo de Datos
El microservicio utiliza un modelo de datos eficiente para almacenar y gestionar información relacionada con usuarios, roles y acceso al aplicativo.

(Descripción del modelo de datos)

## Métodos
### Método 1: `validarUsuario`
- Descripción del método.
- Parámetros y su uso.
- Ejemplo de uso.

### Método 2: `crearSesion`
- Descripción del método.
- Parámetros y su uso.
- Ejemplo de uso.



## Despliegue
1. Clona este repositorio:
    ```bash
    git clone https://github.com/DaniDuran/ms-login-manager.git
    cd ms-login-manager
    ```

2. Configura el archivo de configuración (`appsettings.json`, por ejemplo) con los datos necesarios.

3. Ejecuta las migraciones de la base de datos:
    ```bash
    dotnet ef database update
    ```

4. Inicia el microservicio:
    ```bash
    dotnet run
    ```

## Errores Frecuentes
- Lista de errores comunes y sus soluciones.



## Licencia
Este microservicio está bajo la licencia [`Apache License`]. Ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

---
