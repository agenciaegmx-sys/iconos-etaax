# ETAAX · Iconos administrativos y Gastos diarios

36 iconos SVG independientes en `oscuro/` y `claro/`. Transparentes, viewBox 0 0 24 24, trazo 1.8 px. Oscuro: crema #F0ECE4 y cian #8CE4EE. Claro: tinta #191A17 y azul #247681.

Abre etaax-gastos-diarios.html en el navegador. Incluye lista de gastos, formulario, filtros por periodo, estados de pago, límite de gasto, carga local de nombres de evidencias, exportación CSV, impresión y biblioteca de descargas SVG. Sin dependencias de red.

Los datos son ficticios y se pierden al recargar. No se conecta a cuentas, pagos, autorizaciones ni almacenamiento de archivos. El QR móvil se explica como flujo futuro, no se genera uno ficticio. Gasto mayor (> límite) no se registra hasta conectar autorización real. La asociación de apartados y proveedores es demostrativa. En producción: permisos y clasificación deben validarse en servidor; confirmar reglas contables del negocio.

Propuesta de jerarquía: terracota para acción principal, cian para selección y navegación, neutros para cerrar/minimizar. Los estados tienen texto e icono. El resumen incluye el periodo completo; búsqueda y filtros limitan la tabla y CSV.
