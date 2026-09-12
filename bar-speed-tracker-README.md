# Velocímetro de Barra (Bar Speed Tracker)

Dispositivo basado en ESP32 + IMU que mide la velocidad de la barra durante press, sentadilla y peso muerto, para entrenamiento basado en velocidad (VBT).

**Estado:** 🟡 En desarrollo

## Motivación

<!-- ¿Por qué este proyecto? Conecta tu experiencia como atleta/coach de powerlifting con la necesidad técnica que resuelve. -->

## Cómo funciona

<!-- Explicación general: sensor → cálculo de velocidad → visualización/registro. Un diagrama sencillo (puede ser una foto de un dibujo a mano) ayuda mucho aquí. -->

## Hardware

| Componente | Modelo | Notas |
|---|---|---|
| Microcontrolador | ESP-32 | |
| Sensor de movimiento | GY-6500 (MPU6500) | Acelerómetro + giroscopio, I2C |
| Pantalla | OLED 0.96" | Opcional |
| Alimentación | | |

## Software

<!-- Lenguaje, librerías usadas, estructura del código. Enlaza a la carpeta /src o /firmware del repo. -->

## Diseño mecánico / carcasa

<!-- Fotos o renders del diseño 3D, decisiones de diseño (sujeción a la barra, resistencia a impactos). -->

## Resultados y validación

<!-- Aquí van los datos reales: comparación contra vídeo a cámara lenta, gráficas de velocidad por repetición, con qué atletas se probó. -->

## Problemas encontrados y decisiones

<!-- Lo más valioso del README para un portfolio: qué no funcionó a la primera, qué cambiaste y por qué (ej. drift del acelerómetro, cómo lo corregiste). -->

## Próximos pasos

- [ ]

## Estructura del repositorio

```
/firmware      → código para el ESP32
/hardware      → diseños 3D (STL/STEP), esquema de conexiones
/media         → fotos y vídeos del proceso y del dispositivo
/data          → mediciones y gráficas de validación
README.md
```

## Créditos

Proyecto propio, desarrollado como parte de mi portfolio de Ingeniería Mecánica (UPC).
