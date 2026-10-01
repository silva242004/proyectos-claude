# Simulación del Tren de Alta Velocidad Tokio-Osaka (N700S Shinkansen)

## Prompt Inicial

> Haz una simulación del tren de alta velocidad entre Tokio y Osaka con transparencias y detalle en 3d a nivel profesional con motion graphics incluye detalles de ingeniería

## Resumen Ejecutivo

Simulación interactiva 3D en tiempo real del tren N700S Shinkansen con transparencias, detalles de ingeniería a nivel profesional y motion graphics. La simulación reproduce el viaje completo entre Tokio y Osaka (~2h 20min) con física de movimiento, sistemas de potencia y visualización de componentes técnicos.

## Características Principales

### Tren (Modelado Generado por Código)
- **Modelo:** N700S de 16 coches
- **Componentes:** Nariz aerodinámica, ventanas, asientos, bogies con ruedas rotativas, pantógrafo, baterías SCiB, transformadores y convertidores
- **Transparencias:** Deslizador "Casco" para ver interior y sistemas inferiores; barreras antirruido y techos de andén translúcidos

### Ingeniería y Datos Técnicos
- 11 etiquetas 3D interactivas con información detallada de componentes
- Sistema de cámara que se aproxima a cada componente al seleccionar
- Ficha técnica completa del sistema

### Física de Movimiento
- Conductor automático que acelera/frena respecto a límite de velocidad
- Cálculo de potencia y resistencia al avance
- Panel de instrumento con datos de:
  - Potencia y esfuerzo
  - Tensión y corriente de catenaria
  - RPM del motor y ruedas
  - Inclinación en curvas

### Recorrido
- **17 estaciones reales** en la ruta Tokyo-Osaka
- **Paradas oficiales Nozomi:** Tokio, Shinagawa, Shin-Yokohama, Nagoya, Kyoto, Shin-Osaka

### Motion Graphics
- Título animado de entrada
- Carteles animados en estaciones (llegadas y pasos)
- Mapa interactivo con avance y perfil de velocidad
- Líneas de movimiento y visualización de trenes en sentido contrario
- Ciclo día/noche
- **7 cámaras:** exterior, cabina, vistas dinámicas
- Monte Fuji visible a la derecha (como en la ruta real)

### Controles de Reproducción
- Velocidad: 4×, 16×, 60× en tiempo real
- Botón "Siguiente tramo" que salta ~7km a la próxima parada

## Limitaciones Conocidas

- Terreno estilizado, sin túneles ni topografía real detallada
- Datos técnicos (distribución de baterías, coches con pantógrafo) son plausibles pero no datos oficiales de JR Central
- Viaje en tiempo real puede ser lento en dispositivos móviles por la cantidad de objetos 3D

## Validación

✓ Probado en Chromium sin interfaz: sin errores de JavaScript  
✓ Funciona en escritorio y dispositivos móviles  
✓ Renderiza correctamente sin aceleración GPU verificada
