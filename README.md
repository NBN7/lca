# 🦵 LCA Countdown

Este es un contador en tiempo real para seguir mi recuperación tras la cirugía de LCA. Me permite ver exactamente cuántos días, horas, minutos y segundos han pasado desde mi operación (25 de febrero de 2025) y cuánto tiempo falta hasta completar un año (26 de febrero de 2026).

## 🚀 Características

- 📆 **Cuenta regresiva** hasta el año de recuperación.
- ⏳ **Tiempo transcurrido** desde la operación.
- ⌛ **Actualización en tiempo real** (cada segundo).
- 🎨 **Interfaz simple y clara** con Tailwind CSS.
- 🔧 **Personalizable**: Cualquier persona puede usarlo cambiando las fechas.

## 🔧 Personalización

Si alguien quiere usar este contador para trackear su propio tiempo, simplemente debe modificar las fechas en:

```ts
// src/constants/dates.ts
export const OPERATION_DATE = new Date("YYYY-MM-DD"); // Fecha de inicio
export const TARGET_DATE = new Date("YYYY-MM-DD"); // Fecha objetivo
```

Cambiando `YYYY-MM-DD` por las fechas deseadas, la aplicación mostrará el tiempo transcurrido y restante de acuerdo a la nueva configuración.

## 🛠️ Tecnologías utilizadas

- **Next.js** – Framework de React.
- **TypeScript** – Tipado estático para mayor seguridad.
- **Tailwind CSS** – Estilado rápido y eficiente.

## 📦 Instalación y ejecución

1. Clonar el repositorio:

   ```sh
   git clone https://github.com/tu-usuario/lca-countdown.git
   cd lca-countdown
   ```

2. Instalar dependencias:

   ```sh
   npm install
   # o
   yarn install
   ```

3. Ejecutar en desarrollo:

   ```sh
   npm run dev
   # o
   yarn dev
   ```

4. Abrir en el navegador:
   ```
   http://localhost:3000
   ```

## 📄 Licencia

Este proyecto es personal y no tiene licencia pública.
