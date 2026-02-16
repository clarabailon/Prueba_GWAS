# Calculadora de Poder Estadístico para GWAS (genpwr) 🧬

Esta aplicación interactiva permite calcular el poder estadístico en estudios de asociación de genoma completo (GWAS). Utiliza el motor de R de forma local en el navegador gracias a la tecnología **Shinylive**.

## 🚀 Acceso a la Aplicación
Puedes usar la calculadora directamente aquí: 
https://clarabailon.github.io/Prueba_GWAS/

## 🛠️ Características
- **Cálculo de Poder**: Estima la probabilidad de detectar una asociación genética dado un tamaño de muestra y un efecto.
- **Sin Servidores**: A diferencia de las apps de Shiny convencionales, esta aplicación se ejecuta íntegramente en tu navegador. Esto garantiza:
  - **Privacidad**: Tus datos no salen de tu ordenador.
  - **Disponibilidad**: Sin límites de tiempo de uso ni restricciones de servidor.
  - **Escalabilidad**: Muchos usuarios pueden usarla simultáneamente sin ralentizar el sistema.

## 📦 Paquetes Utilizados
La aplicación está construida en **R** utilizando las siguientes librerías:
- `shiny`: Interfaz de usuario.
- `genpwr`: Motor de cálculos genéticos.
- `ggplot2`: Visualización de resultados.
- `shinylive`: Exportación a WebAssembly para ejecución sin servidor.

## 📝 Notas de Uso
Al abrir la aplicación por primera vez, puede tardar unos segundos en cargar. Esto se debe a que el navegador está descargando un "mini-entorno" de R y las librerías necesarias para que la app funcione sin conexión a un servidor central.
