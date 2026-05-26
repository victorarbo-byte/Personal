# 🏃 Media Maratón Barcelona — Plan 15 Semanas

Plan de entrenamiento personalizado para la **Media Maratón de Barcelona (febrero)**.  
Objetivo: **Sub 1:50h** · Ritmo objetivo: **5:13/km**

🔗 **[Ver plan en vivo](https://victorarbo-byte.github.io)**

-----

## 📋 Descripción

Plan interactivo de 15 semanas con progresión gradual de ritmo (6:10 → 5:13/km), combinando running y fuerza funcional. El progreso se sincroniza entre dispositivos a través de Supabase.

-----

## 🗓️ Estructura del plan

|Bloque          |Semanas|Objetivo                         |Ritmo       |
|----------------|-------|---------------------------------|------------|
|1 · Base        |1–3    |Base aeróbica + activación fuerza|6:10–5:50/km|
|2 · Construcción|4–7    |Volumen + fuerza máxima          |5:45–5:20/km|
|3 · Velocidad   |8–12   |Velocidad específica + potencia  |5:18–5:13/km|
|4 · Tapering    |13–15  |Simulacros + puesta a punto      |5:13/km     |

-----

## 📅 Semana tipo

|Día    |Sesión                 |
|-------|-----------------------|
|Lunes  |💪 Fuerza piernas + core|
|Martes |⚡ Intervalos / Tempo   |
|Jueves |🏃 Rodaje suave         |
|Sábado |🏋️ Fuerza tren superior |
|Domingo|📏 Tirada larga         |

-----

## 🏋️ Equipamiento

- Polea alta/baja
- Mancuernas
- Barra

-----

## 📊 Resumen

- **15 semanas** · **75 sesiones** totales
- Tirada larga máxima: **18 km** (semana 11)
- Tests de progreso: semanas **3, 7 y 12**
- Semana de carrera: **semana 15**

-----

## ⚙️ Stack técnico

- **Frontend:** HTML + CSS + JS vanilla
- **Hosting:** GitHub Pages
- **Base de datos:** Supabase (progreso sincronizado entre dispositivos)

-----

## 🚀 Setup local

```bash
# Clona el repositorio
git clone https://github.com/victorarbo-byte/plan-running.git

# Abre el archivo directamente en el navegador
open index.html
```

Para sincronización entre dispositivos necesitas configurar tus propias credenciales de Supabase en `index.html`:

```js
const SUPABASE_URL = 'https://tu-proyecto.supabase.co';
const SUPABASE_KEY = 'tu-anon-key';
```

-----

*Plan diseñado con Claude · gbfoods 2026*