<img alt="exchangeimg" width="200px" height="200px" align="right" src="https://images.vexels.com/media/users/3/146882/isolated/preview/7525685ed67fa782b7d851273e1264c7-cambio-de-divisas.png">

# Conversor de Monedas 💱

¡Bienvenido/a! Esta es una aplicación desarrollada en **Java 17** que te permite convertir monedas de manera fácil y rápida, consumiendo datos actualizados de la API de [ExchangeRate-API](https://www.exchangerate-api.com/).

> 🚀 Proyecto desarrollado como parte del programa ONE - Oracle Next Education (Backend)

## 📋 Tabla de Contenidos
- [Características Principales](#características-principales)
- [Cómo Funciona](#cómo-funciona)
- [Demostración](#demostración)
- [Configuración del Entorno](#configuración-del-entorno)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)

## ✨ Características Principales

La aplicación ofrece un menú interactivo con las siguientes opciones:

1. **Convertir monedas** - Realiza conversiones entre diferentes divisas
2. **Ver listado de monedas** - Consulta las monedas disponibles
3. **Agregar nueva moneda** - Amplía tu lista personalizada
4. **Eliminar moneda** - Gestiona tu listado
5. **Historial de conversiones** - Revisa tus conversiones anteriores
7. **Salir** - Cierra la aplicación

### Listado inicial de monedas:
| # | Código | Moneda |
|---|--------|--------|
| 1 | ARS | Peso argentino |
| 2 | BOB | Boliviano boliviano |
| 3 | BRL | Real brasileño |
| 4 | CLP | Peso chileno |
| 5 | COP | Peso colombiano |
| 6 | USD | Dólar estadounidense |

## 🎯 Demostración

### 1. Realizar una conversión
Al seleccionar la opción 1, podrás:
- Elegir la moneda de origen
- Seleccionar la moneda destino
- Ingresar el monto a convertir
- ¡Obtener el resultado al instante!

### 2. Gestionar tu listado de monedas
La aplicación te permite personalizar tu experiencia:
- **Agregar monedas**: Explora más de 150 divisas soportadas por la API
- **Eliminar monedas**: Mantén solo las que necesitas (mínimo 2 para conversiones)

### 3. Historial de conversiones
Todas tus conversiones quedan registradas para que puedas consultarlas cuando quieras.

## 🛠️ Configuración del Entorno

### Requisitos previos
- Java 17 o superior
- IDE (recomiendo IntelliJ IDEA)
- Conexión a internet

### Pasos para configurar

1. **Obtén tu API Key gratuita**
   - Regístrate en [ExchangeRate-API](https://www.exchangerate-api.com/)
   - Confirma tu email para activar la clave

2. **Configura la variable de entorno**
EXCHANGE-API-KEY=tu_api_key_aqui

text

En terminal/Linux:
```bash
export EXCHANGE-API-KEY="tu_api_key_aqui"
Ejecuta la aplicación

Compila y ejecuta src/Main.java

¡Listo! Ya puedes comenzar a convertir

💻 Tecnologías Utilizadas
Java 17 - Lenguaje principal

ExchangeRate-API - API de conversión de divisas

Gson - Procesamiento de JSON

IntelliJ IDEA - Entorno de desarrollo

📝 Notas importantes
La aplicación mantiene un caché local de monedas para optimizar las consultas a la API

No es posible eliminar todas las monedas (mínimo 2 para conversiones)

El historial se mantiene durante la sesión actual   
   En IntelliJ IDEA:
   - Ve a `Run` → `Edit Configurations`
   - En `Environment variables`, agrega:
