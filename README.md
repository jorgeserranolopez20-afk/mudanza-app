# Mudanza App - Cotizador Inteligente

Aplicación web diseñada para optimizar la selección de camiones de mudanza, evitando gastos extra y pérdidas por estimaciones incorrectas de espacio. El sistema calcula la capacidad exacta requerida y el precio del servicio basado en volumen y distancia.

## Funcionalidades Principales

- Cotizador Espacial Interactivo: Interfaz visual (estilo Tetris) que permite al usuario organizar sus pertenencias utilizando una unidad de medida estándar (UC de 1x1) para calcular el volumen exacto.
- Estimación Automatizada con IA: Opción para subir una lista de objetos en texto; una inteligencia artificial la analiza y genera automáticamente la estimación de espacio requerido.
- Cálculo de Tarifas Dinámico: Cotización final basada en el tipo de camión sugerido y la distancia del trayecto (mediante selección de comuna a comuna).
- Roles y Autenticación: Inicio de sesión con accesos separados para clientes y administradores.
- Panel de Administración: Sistema CRUD completo para la gestión de cuentas de usuarios y el control de las solicitudes de mudanza.

## Tecnologías Utilizadas

- Frontend: React, Vite, Tailwind CSS, TypeScript
- Backend: Node.js
- Base de Datos: PostgreSQL
- Integración IA: Procesamiento de listas y estimación volumétrica

## Estructura del Frontend

El frontend de la aplicación está construido con componentes de React que modularizan las vistas principales:
- `Auth.tsx`: Gestión del inicio de sesión.
- `Dashboard.tsx`: Panel principal de control.
- `LoadAssistant.tsx`: Interfaz interactiva de organización espacial.
- `Recommendation.tsx`: Sugerencias de tipo de camión basadas en el volumen calculado.
- `Uploads.tsx`: Módulo para subir las listas de objetos que analiza la IA[cite: 9, 10].
