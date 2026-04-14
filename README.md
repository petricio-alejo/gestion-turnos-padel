# Sistema de Reserva de Turnos - Padel

## Descripción
Sistema de reserva de turnos para canchas de padel con funcionalidades de gestión de reservas y notificaciones.

## Requisitos Previos
- Node.js (v18+)
- npm

## Instalación

### Backend
```bash
cd backend
npm install
```

### Frontend
```bash
cd frontend
npm install
```

## Ejecución

### Backend
```bash
cd backend
npm run dev
```
El backend correrá en: http://localhost:3000

### Frontend
```bash
cd frontend
npm run dev
```
El frontend correrá en: http://localhost:5173

## Reglas de Negocio
- Las canchas tienen reservas de 1 hora y media (de las 18:00 hasta las 19:30)
- Una misma cancha no puede tener dos turnos en el mismo horario
- Todas las canchas tienen el mismo precio
- Las cancelaciones deben hacerse con mínimo 12 horas de antelación

## Patrones de Diseño

### Singleton
Para garantizar una sola conexión compartida a la base de datos.

### Observer
Para notificar a los usuarios cuando un turno de su interés esté disponible.

## Integrantes
- Ezequiel Barrionuevo
- Franco Muñoz Cartagena
- Alejo Petricio
- Parotta Luciano
