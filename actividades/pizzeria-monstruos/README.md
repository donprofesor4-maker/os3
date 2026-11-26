# Pizzería de Monstruos · OS3

Juego individual de tercero de primaria: cuentas en vertical con productos parciales, agrupación C/D/U, equivalencias de diez, cocina y decoración.

## Contenido

- 24 pedidos en 4 turnos: decenas sin reagrupación, decenas con reagrupación, centenas sin reagrupación y centenas con reagrupación.
- 6 clientes ilustrados y 4 ingredientes.
- Tres etapas por pedido: cuenta con casillas y pistas, preparación de la cantidad y acabado de una pizza de muestra.
- Cambios de 10 unidades por 1 decena y de 10 decenas por 1 centena.
- Tres estrellas por cada pedido completado; 25 monedas una sola vez por pedido. Los reintentos y pistas no reducen premios.
- Cuatro decoraciones que se compran con monedas del juego.
- Progreso local, sonido opcional y reducción de movimiento.
- Turnos disponibles desde el inicio para permitir la selección de la maestra.

No hay reloj, vidas, compras reales, cuentas ni datos personales. Solo se conserva el progreso en el navegador (clave `monsterPizzaOS3-v1`). Recargar reinicia el pedido actual; se conservan entregas y compras. No hay registro central de resultados por alumno.

Arte SVG original y efectos sonoros sintetizados de DonProfesor. Sin imágenes de terceros ni dependencias JavaScript. Tipografías Baloo 2 y Nunito a través de Google Fonts, con fuentes de sistema como respaldo.

## Verificación

Desde la raíz del repositorio: `node tests/pizzeria.cjs`.

El motor puro en `engine.js` contiene pedidos, productos parciales, casillas, validación C/D/U y economía. `game.js` maneja el flujo y `art.js` las ilustraciones originales.
