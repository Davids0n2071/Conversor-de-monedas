# Conversor-de-monedas

## 📋 Descripción del Proyecto

Este proyecto fue desarrollado como parte del programa Oracle Next Education (ONE) - LATAM, implementando los siguientes conceptos fundamentales:

- Programación orientada a objetos con Java
- Integración con APIs externas mediante la librería GSON
- Gestión de excepciones y errores
- Organización de proyectos y configuración mediante archivos

**Objetivo principal:** Crear una aplicación práctica que consuma una API de tasas de cambio para realizar conversiones monetarias en tiempo real.

La aplicación ofrece funcionalidades de conversión entre divisas, mantenimiento de un historial de conversiones realizadas y una guía completa con todas las combinaciones de monedas disponibles.

## 🔑 Obtención de la API Key

1. Accede a [ExchangeRate-API](https://www.exchangerate-api.com)
2. Selecciona la opción "Get Free API Key"
3. Completa el registro con tu correo electrónico
4. Tu clave API personal será proporcionada en el panel principal después del inicio de sesión

## ⚙️ Instalación y Configuración

### 1. Clonar el repositorio
```bash
git clone https://github.com/aquilescb/conversor_de_monedas
cd conversor_de_monedas
```
### 2. Configurar tu propia API Key
Creá un archivo llamado `config.properties` dentro de la carpeta `src`
Dentro de ese archivo, agregá `API_KEY` y luego tu clave generada:
```bash
API_KEY=TU_CLAVE_AQUI
```
### 3. Instalar la libreria GSON
1. Descargá el archivo .jar de GSON desde este enlace: [GSON](https://mvnrepository.com/artifact/com.google.code.gson/gson)
(Recomendacion:descargar la última version)
3. En IntelliJ IDEA:
   - Ir a *file> Project Structre > Modules > Dependencies*
   - Hacer clic en el boton "+" y seleccionar "JARs or directories"
   - Elegi el archivo `.jar` descargado
   - Aplica los cambio

---
## ▶️ Ejecutar el programa
Desde IntelliJ IDEA
1. Asegurate de tener `config.properties` accesible en el classpath.
2. Ejecutá la clase `ConversorApp`
