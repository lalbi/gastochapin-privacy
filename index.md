# Política de privacidad — GastoChapín

**Última actualización:** 25 de abril de 2026

GastoChapín ("la app") es una aplicación móvil para el control de gastos personales, hecha en Guatemala por **Luis Albizures** ("el desarrollador"). Esta política explica qué datos maneja la app, dónde se almacenan y qué control tenés sobre ellos.

## Resumen rápido

- La app **funciona 100% offline**. Tu información se guarda solo en tu celular, **no en servidores nuestros ni de terceros**.
- **No usamos tracking, ni publicidad, ni perfiles de comportamiento.**
- Las únicas comunicaciones de red que la app realiza son: ninguna obligatoria. Las opcionales (envío de feedback por correo) requieren tu acción explícita.
- Si desinstalás la app, todos tus datos se borran del dispositivo.

## Qué información maneja la app

### Datos que vos ingresás manualmente

- **Perfil:** nombre, correo, teléfono, moneda preferida, presupuesto mensual.
- **Gastos e ingresos:** monto, fecha, categoría, descripción, método de pago.
- **Recurrentes:** nombre, empresa, monto, frecuencia, fechas de vencimiento.
- **Fotos adjuntas a gastos:** se guardan en almacenamiento privado del dispositivo (`storage interno`). Solo la app puede acceder a ellas. Al eliminar el gasto, la foto se borra automáticamente.

### Datos que importás desde archivos SAT

- **Facturas Electrónicas FEL** (XML o JSON v2): si las cargás vía Más → Importar facturas SAT, la app extrae y almacena: NIT del emisor, nombre fiscal y comercial, dirección, tu NIT, número de autorización SAT (UUID), montos, IVA, fecha de emisión, certificador, lista de productos/servicios.

Toda esta información queda **únicamente en la base de datos local de tu celular**.

### Permisos de Android que usa la app

- **Notificaciones (`POST_NOTIFICATIONS`)**: para recordarte 3 días y 1 día antes del vencimiento de tus recurrentes, y opcionalmente recordatorios diarios de gastos. Vos controlás si querés recibirlas desde Más.
- **Cámara (`CAMERA`)**: solo si tocás "Agregar foto" en un gasto. La foto se guarda en almacenamiento privado.
- **Almacenamiento de medios (`READ_MEDIA_IMAGES`)**: solo si elegís adjuntar una foto desde la galería en lugar de tomarla con la cámara.
- **Reinicio del dispositivo (`RECEIVE_BOOT_COMPLETED`)**: para reagendar tus recordatorios de recurrentes después de reiniciar el celular.
- **Acceso a archivos vía SAF**: cuando importás XMLs o JSON, Android te pide elegir el archivo. La app no lee nada que vos no hayas seleccionado explícitamente.

## Qué NO hace la app

- ❌ **No envía datos a servidores nuestros.** Los gastos, facturas, fotos y demás información permanecen en tu dispositivo.
- ❌ **No usa servicios de analytics** (Google Analytics, Firebase Analytics, Mixpanel, etc.).
- ❌ **No muestra publicidad** ni comparte información con anunciantes.
- ❌ **No vende ni comparte tus datos** con terceros.
- ❌ **No requiere cuenta de usuario** ni inicio de sesión.
- ❌ **No accede a tus contactos, ubicación, calendario, mensajes, llamadas ni redes sociales.**

## Comunicaciones de red opcionales

La única forma en que la app accede a internet es si vos lo iniciás:

- **Botón "Enviar feedback"** (Más → Enviar feedback): abre tu app de correo (Gmail, Outlook, etc.) con un mensaje pre-llenado dirigido a `lalbizures@gmail.com`. Vos decidís si lo enviás. Si no tocás "enviar", no se envía nada. La app no envía correos automáticamente.

- **Botón "Calificar en Play Store"** (Más): abre Play Store en una pantalla pública de la app. No comparte datos tuyos.

## Control de tus datos

- **Eliminar un gasto/recurrente:** desde la pantalla de detalle, tocá Eliminar.
- **Borrar todos los datos:** desinstalá la app desde los ajustes de Android (Ajustes → Apps → GastoChapín → Desinstalar). Esto borra la base de datos completa, las fotos adjuntas y tus preferencias.
- **Exportar tus datos:** desde Más → Exportar facturas SAT podés generar un archivo JSON con tu historial de facturas para backup.

## Seguridad

- La base de datos vive en almacenamiento privado de la app, accesible solo al sistema operativo y a la propia app. Otras apps no pueden leerla.
- No transmitimos información por la red, así que no hay riesgo de intercepción.
- Si tu dispositivo está comprometido (rooteado, infectado, etc.), un atacante con acceso físico al dispositivo podría acceder a la BD. Por eso recomendamos mantener tu Android actualizado y con bloqueo de pantalla activo.

## Niños

GastoChapín no está dirigida a menores de 13 años. No solicita información personal de niños deliberadamente. Si sos padre/madre y notás que tu hijo está usando la app, podés desinstalarla en cualquier momento.

## Cambios a esta política

Si en versiones futuras incorporamos features que requieran enviar datos a servidores (ej. respaldo en nube opcional), actualizaremos esta política y te avisaremos vía la app antes de activarlas. Cualquier cambio relevante lo verás reflejado en la fecha de "Última actualización" arriba.

## Contacto

Para dudas, pedidos o reportes relacionados con privacidad o el manejo de tus datos:

**Luis Albizures**
**Correo:** lalbizures@gmail.com

Te respondemos lo más rápido que podamos. Como la app es offline, no tenemos forma de identificar tu instalación particular — al escribirnos describí lo que querés saber o reportar y con gusto te ayudamos.

---

*GastoChapín — hecho en Guatemala 🇬🇹*
