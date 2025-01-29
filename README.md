
# Aplicación de Clima con React y TypeScript

Esta es una aplicación web que permite consultar el clima actual de diferentes ciudades alrededor del mundo utilizando la API de OpenWeather.

## Tecnologías Utilizadas

- React 18.3
- TypeScript
- Vite
- CSS Modules
- Zod (para validación de tipos en runtime)
- Axios (para peticiones HTTP)
- ESLint

## Aprendizajes Clave

- Implementación de TypeScript en un proyecto React
- Uso de CSS Modules para estilos modulares
- Manejo de estados y efectos con React Hooks
- Validación de tipos en runtime con Zod
- Consumo de APIs externas con Axios
- Manejo de variables de entorno en Vite
- Implementación de componentes reutilizables
- Gestión de formularios controlados
- Manejo de errores y estados de carga

## Características

- Búsqueda de clima por ciudad y país
- Muestra temperatura actual, máxima y mínima
- Interfaz responsiva
- Manejo de estados de carga y errores
- Validación de formularios
- Conversión automática de temperaturas Kelvin a Celsius

## Cómo ejecutar el proyecto

1. Clona el repositorio:
```bash
git clone [URL del repositorio]
```

2. Instala las dependencias:
```bash
npm install
```

3. Crea un archivo `.env` en la raíz del proyecto y agrega tu API key de OpenWeather:
```bash
VITE_API_KEY=tu_api_key_aqui
```

4. Inicia el servidor de desarrollo:
```bash
npm run dev
```

5. Abre tu navegador en `http://localhost:5173`

## Scripts Disponibles

```bash
npm run dev      # Inicia el servidor de desarrollo
npm run build    # Construye la aplicación para producción
npm run lint     # Ejecuta el linter
npm run preview  # Previsualiza la versión de producción
```

## Estructura del Proyecto

El proyecto sigue una estructura modular con:
- Componentes reutilizables
- Hooks personalizados
- Utilidades y tipos TypeScript
- Estilos modulares con CSS Modules
- Configuración de TypeScript y ESLint

## Notas Adicionales

- La aplicación requiere una API key válida de OpenWeather para funcionar
- Los estilos están optimizados para dispositivos móviles y escritorio
- Se implementan buenas prácticas de TypeScript y React