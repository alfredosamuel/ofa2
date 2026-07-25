# Contexto del proyecto

Este archivo describe el contenido y la finalidad de la página principal del proyecto, representada por el archivo index.html.

## Propósito general

La página funciona como un panel de trading avanzado y visualización de mercados financieros. Está orientada a mostrar gráficos de precio, indicadores técnicos, flujo de órdenes, alarmas, backtesting y opciones de integración con Telegram.

## Estructura principal

- Header superior: muestra el logo, el selector de activo, un campo para ingresar otro símbolo y un estado de conexión.
- Barra de herramientas: permite cambiar el layout de la vista, seleccionar timeframes y activar o desactivar indicadores.
- Área central: contiene una grilla de gráficos interactivos donde se renderizan los datos del mercado.
- Panel lateral: incluye pestañas para:
  - Flow: métricas del candle actual, estadísticas 24h e historial de eventos.
  - Alarmas: gestión de alertas visuales y de notificación.
  - Backtest: simulación de estrategias sobre datos históricos.
  - Telegram: configuración para probar integración con un bot.
- Pie de página: muestra información de datos y ayuda contextual.

## Funcionalidades destacadas

- Selector de activos como BTC/USDT, ETH/USDT, SOL/USDT, oro, Nasdaq y dólar CLP.
- Cambio de timeframe entre 1m, 5m, 15m, 1h, 4h, 1D y 1W.
- Activación de indicadores técnicos como SMA, VWAP, bandas VWAP, OrderFlow, fractales, Volume Profile, VP Fractal y ADX.
- Herramientas de dibujo y marcación sobre el gráfico.
- Alarmas mediante interacción con el gráfico.
- Backtest de estrategia con parámetros configurables.
- Integración con Telegram para enviar pruebas o alertas.

## Estilo visual

La interfaz utiliza un diseño oscuro, tipo terminal/cyber, con colores cian, magenta, verde y ámbar. Se enfoca en una experiencia visual tipo dashboard profesional.

## Tecnologías visibles en la página

- HTML5 estructural.
- CSS personalizado para layout, componentes y temas.
- JavaScript embebido para interacción, lógica de indicadores, UI y simulación.
- Biblioteca Lightweight Charts para renderizar gráficos.

## Resumen breve

El archivo index.html representa una herramienta de análisis técnico interactiva para operadores, con foco en visualización de mercados, señales, backtesting y alertas en tiempo real o simuladas.
