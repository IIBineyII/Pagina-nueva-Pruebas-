# Rueda Libre v1.5

Base de referencia para iniciar semana 2 día 2 de HTML y CSS de Riwi. Implementa el resultado técnico hasta semana 2 día 1. Es una implementación didáctica nueva basada en los retos de Moodle, no una copia del repositorio de un coder.

## Abrir el proyecto
1. Extrae el ZIP completo. Abre la carpeta rueda-libre-v1.5 con VS Code.
2. Abre index.html con Live Server. También puedes abrirlo directamente en el navegador para consultar el sitio.
3. Recorre Inicio, Tarifas y rutas, y Reservas. Las imágenes SVG son locales. Google Fonts requiere internet; hay fuentes de respaldo.
4. Lee la guía antes de agregar Bootstrap. Este proyecto todavía usa CSS propio.

## Qué contiene
- Tres páginas semánticas enlazadas, tablas accesibles y formulario completo con validación nativa.
- Paleta de marca, Montserrat y Open Sans, variables, selectores, estados y modelo de caja.
- Encabezado y pie con Flexbox; flota de siete modelos con Grid auto-fit; tarjetas con Flexbox; portada, rutas y formulario con Grid; enfoque mobile-first.
- Rutas locales e ilustraciones SVG creadas para este material. Son referencias visuales, no fotografías ni representaciones exactas de modelos comerciales. Puedes reemplazarlas por fotos propias conservando las rutas y actualizando alt.
- Acceso fijo a WhatsApp de ejemplo y etiqueta Nuevo en la bicicleta eléctrica.

## Límites del ejemplo
No incluye Bootstrap ni tareas resueltas del día 2. No tiene backend ni JavaScript propio. El formulario conserva method="post" del reto: el navegador valida antes del envío, pero un servidor estático no procesa la reserva. Un error 405 o 501 después de pasar la validación no significa que los campos estén mal. Nunca se confirma ni se almacena una reserva en este proyecto. Prueba con datos ficticios.

Las fechas 2026-11-01 a 2026-12-31 corresponden al caso de Moodle. Para reutilizarlo en otra cohorte, actualiza ambas fechas y las pruebas.

## Antes de migrar
La hoja CSS está dividida en secciones comentadas. Conserva una referencia con Git antes de modificarla. No hay un historial de trabajo estudiantil inventado ni publicación ya realizada. La bitácora trae espacios por completar con observaciones reales. Sigue los mini retos 5 a 8 de la guía.

## Git y publicación
Si empiezas un repositorio nuevo: git init, git add ., git commit -m "Base Rueda Libre v1.5", git branch -M main. Crea un repositorio vacío en tu cuenta, conecta su URL con git remote add origin URL y ejecuta git push -u origin main. En GitHub, Settings > Pages > Deploy from a branch > main > / (root). Guarda la URL que realmente genere GitHub.

## Datos y fuente curricular
Página T1.1 HTML y CSS, Moodle Riwi, consultada el 30 de octubre de 2026: https://moodle.riwi.io/mod/page/view.php?id=7605
Se siguen los mini retos completos. El séptimo modelo es Tándem. La guía aplica en Bootstrap una, dos, tres y cuatro columnas según los mini retos, aunque el laboratorio resumido use seis modelos y otro reparto.
