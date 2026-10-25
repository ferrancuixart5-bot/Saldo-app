# Saldo — versión web instalable para iPhone

Este es un prototipo web responsive que funciona en Safari y guarda los datos en el almacenamiento local del navegador del dispositivo.

## Probar en iPhone
Safari necesita una dirección web para ofrecer “Añadir a pantalla de inicio”. La manera gratuita más sencilla es publicar estos archivos en GitHub Pages:
1. Crea una cuenta en GitHub y un repositorio público nuevo llamado `saldo`.
2. Sube `index.html`, `manifest.json` y `sw.js` a la raíz del repositorio.
3. En Settings → Pages, elige desplegar desde la rama principal (root).
4. Abre la URL HTTPS que GitHub Pages te da en Safari en el iPhone.
5. Pulsa Compartir → Añadir a pantalla de inicio.

También puedes abrir `index.html` localmente en un navegador de escritorio para una prueba rápida.

## Incluye
- Dashboard de balance mensual
- Añadir ingresos y gastos
- Categorías y fechas
- Presupuesto editable y aviso al 80 %
- Resumen por categorías
- Guardado local del navegador
- Pantalla conceptual de Saldo Plus

## Limitaciones
No es una app nativa compilada ni publicada en App Store. No tiene pagos reales, sincronización entre dispositivos ni copia de seguridad. Los datos viven en el almacenamiento del navegador y pueden perderse si se borra. Los movimientos de ejemplo son ficticios. Antes de uso real, validar y probar a fondo el código y preparar privacidad, accesibilidad y seguridad.
