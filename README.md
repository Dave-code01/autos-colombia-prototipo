# Autos Colombia · Prototipo final

Prototipo navegable del sistema de información del parqueadero **Autos Colombia**, para el control de entrada, salida y ocupación de celdas de vehículos.

**Ver el prototipo:** https://dave-code01.github.io/autos-colombia-prototipo/

Proyecto Integrado I – Desarrollo de Aplicaciones · Institución Universitaria Digital de Antioquia

Equipo: Jeferson Cataño Carmona, Ana Osorio y David Castro Mora · Docente: José Nelson Palacio Londoño

## Cómo probarlo

Dentro del prototipo, el botón **«¿Cómo probar?»** explica el flujo principal y las placas de prueba.

1. **Registrar entrada:** escriba `ABC-123` (con o sin guion), revise la vista previa del vehículo y pulse Enter. Verá la celda asignada.
2. **Vehículos dentro** o **Estado de celdas:** busque la placa para ubicar el vehículo.
3. **Registrar salida:** desde la fila del vehículo, confirme la salida. La celda queda libre.
4. **Historial:** filtre por placa y vea la entrada, la salida y la permanencia.

| Placas de prueba | Uso |
|---|---|
| ABC123, DEF456, XYZ12A | Pueden entrar |
| GHI789, JKL012, MNO34B | Ya están dentro (para registrar la salida) |
| STU789 | Mensualidad no vigente (mensaje de error) |
| QWE999 | Placa no registrada (mensaje de error) |

## Cambios de la versión final (Actividad 3)

Mejoras incorporadas a partir de la validación con usuarios:

- **M1:** la placa acepta guiones, puntos y espacios (ABC-123 = ABC123).
- **M2:** vista previa del vehículo y de su estado mientras se escribe la placa.
- **M3:** botón «Registrar salida» en cada fila de Vehículos dentro y sugerencias de placas en la salida.
- **M4:** buscador por placa en Vehículos dentro y en Estado de celdas, que resalta la celda.
- **M5:** menú en cuadrícula en tablet y celular, sin opciones ocultas.
- **M6:** panel con celdas «libres de N» y barras de ocupación por tipo.
- **M7:** columna «Permanencia» en el historial y tiempo de permanencia al confirmar la salida.
- **M8:** guía de prueba, datos conservados al recargar la página, botón para reiniciar los datos y corrección del botón «Registrar otra entrada».

El prototipo funciona con datos de prueba en el navegador, sin base de datos (iteración 1).
