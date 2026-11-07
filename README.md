# Smart-Vend X1: Módulo aritmético y de control de cambio

Práctica 2-3 de Electrónica Digital (Parcial 2, componente práctico), Universidad Pontificia Bolivariana.

Circuito combinacional y secuencial, sin microcontrolador, que acumula el crédito ingresado moneda a moneda, lo compara con el precio del producto elegido y muestra el cambio en un display de 7 segmentos. Si el crédito no alcanza, el display muestra 0 y se enciende un LED de alerta.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| Informe.pdf | Informe técnico: justificación, análisis aritmético, tabla de verdad, diagrama de bloques y configuración de los integrados |
| Esquematico.pdf | Esquemático de la simulación exportado de Tinkercad |
| Diseño_Tinkercad.png | Vista del circuito en la protoboard virtual |
| Simulacion.mov | Video con las pruebas de la simulación |
| Montaje/ | Fotos y video del montaje físico |
| Rubrica.pdf | Rúbrica diligenciada |

## Parámetros asignados

Último dígito de la cédula: 8 (par), entradas activas en alto con resistencias pull-down de 10 kΩ.
Último dígito del ID: 8 (par), con crédito insuficiente el display muestra 0.

## Uso

El pulsador Moneda suma un crédito ($1000) por cada pulsación. El pulsador Reset devuelve el crédito a cero. Las posiciones 1 (P0) y 2 (P1) del DIP switch seleccionan el producto: 00 reposo, 01 producto de $1000, 10 producto de $2000 y 11 producto de $3000.
