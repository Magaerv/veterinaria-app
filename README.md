# Veterinaria App

Una aplicación web para gestionar citas en una clínica veterinaria.

## Instalación

```bash
git clone https://github.com/Magaerv/veterinaria-app.git
cd veterinaria-app
npm install
```

## Uso

```bash
npm run dev
```

Para utilizar la aplicación, sigue estos pasos:

1. Agrega una cita para una mascota completando todos los campos: Nombre de la mascota, nombre del dueño, fecha, hora y sintomas.
2. Visualiza las citas programadas.
3. Elimina citas cuando sea necesario.

## Ejemplo

![Captura de Pantalla](/src/assets/Veterinaria-administrador-de-citas.png)

```javascript
// Ejemplo de código
const cita = {
  mascota: "Firulais",
  propietario: "Juan Pérez",
  fecha: "2023-09-22",
  hora: "14:30",
  sintomas: "Fiebre alta",
}