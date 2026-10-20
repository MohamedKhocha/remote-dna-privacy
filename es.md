# REMOTE DNA — Política de privacidad

[English](./) · [العربية](ar.html) · [Français](fr.html) · [Português](pt.html) · [中文](zh.html)

> Esta es una traducción. Si hay alguna diferencia, el [texto en inglés](./) es el que vale.

**Fecha de entrada en vigor:** 18 de agosto de 2026 · **Última actualización:** 20 de octubre de 2026

REMOTE DNA («la App») es un control remoto universal para TV y aires
acondicionados, publicado por **Solar AI Systems** (Mohamed Khocha), Argelia.

Esta política describe exactamente lo que la App recopila y lo que no. Se
mantiene al día con la versión publicada.

## Resumen

- Todo lo que necesitas para controlar tus equipos funciona **sin internet**, en
  tu teléfono.
- La App funciona **sin cuenta**. La cuenta es opcional y solo sirve para
  recuperar una licencia Pro pagada en un teléfono nuevo.
- Nunca vendemos tus datos ni los usamos para perfiles publicitarios.

## 1. Datos que se quedan solo en tu dispositivo

Lo siguiente nunca sale de tu teléfono:

- Tus dispositivos guardados, sus conjuntos de códigos y cualquier botón que le
  hayas enseñado a la App («Enseñar mi TV», «Arreglar un botón»).
- Las preferencias de idioma, tema y bienvenida. Hasta que elijas un idioma, la
  App sigue el idioma de tu teléfono, leído en el propio dispositivo.
- Tu clave de licencia Pro y tu token de sesión (en el Android Keystore, con
  almacenamiento cifrado).
- Los datos de vinculación Wi‑Fi de tus TV: la clave que entrega una TV LG o
  Samsung cuando aceptas la conexión y, en Android TV, un certificado de cliente
  generado en el Android Keystore junto con la huella del certificado de la TV.
  Permiten reconectar sin volver a preguntar y solo se usan en tu red doméstica.
- Para un aire Gree por Wi‑Fi, la clave de cifrado que el equipo entrega a la App
  al vincularlo; para el control Bluetooth, la dirección Bluetooth de la TV
  emparejada. Solo se usan para llegar a ese dispositivo.

Desinstalar la App borra todo esto.

## 2. Cuenta opcional

Si —y solo si— creas una cuenta, guardamos en nuestro servidor:

- Tu **correo electrónico**.
- Un **hash criptográfico** de tu contraseña (PBKDF2-HMAC-SHA256). Nunca
  guardamos ni vemos tu contraseña real.
- La fecha de creación de la cuenta y la licencia Pro vinculada a ella.

Finalidad: recuperar tu licencia Pro en un teléfono nuevo y restablecer tu
contraseña.

Los **correos para restablecer la contraseña** se envían a través de Resend
(resend.com). Solo se transmiten tu correo y un código temporal de 6 dígitos.

Puedes pedir que se elimine tu cuenta en cualquier momento: consulta la
sección 8.

## 3. Pagos

Pro es una compra única. La forma de pago depende de dónde instalaste la App, y
esta sección indica el procesador de pagos en cada caso.

- **Si instalaste la App desde Google Play** — la única forma de compra dentro de
  la App es **Google Play Billing**, gestionada con RevenueCat, que identifica tu
  compra con un identificador anónimo. No recibimos datos de tarjeta.
- **Si instalaste la App directamente desde nuestro sitio web** (la versión que
  se distribuye fuera de Google Play) — el pago lo procesa **Chargily Pay** en su
  propia página segura. Los datos de tu tarjeta se ingresan en el sitio de
  Chargily y **ni la App ni nosotros los vemos, procesamos ni guardamos nunca**.
  Chargily nos envía la referencia, el monto y el estado de la transacción, y su
  propia política de privacidad se aplica a lo que ingreses allí. Esta forma no
  se ofrece en la versión de Google Play.

En ambos casos solo guardamos la referencia, el monto, el estado de la
transacción y la clave de licencia emitida.

## 4. Publicidad

La versión gratuita muestra anuncios de **Google AdMob**:

- un **anuncio al abrir** la App (nunca en el primer inicio, y al volver desde
  segundo plano solo tras una ausencia larga);
- de vez en cuando un **anuncio a pantalla completa entre pantallas**;
- un **video corto con recompensa** cada tres usos de «Arreglar un botón».

Entre dos anuncios a pantalla completa siempre pasan al menos tres minutos. No
hay banners. Si no se puede mostrar un anuncio, la App sigue sin él.

- Los anuncios se piden solo con la **clasificación «G» (todo público)** y
  empiezan **sin sonido**.
- En el EEE, el Reino Unido y Suiza se muestra un **formulario de consentimiento
  (Google UMP)** antes de pedir cualquier anuncio, y se respeta tu elección.
- AdMob puede procesar identificadores del dispositivo para mostrar anuncios y
  limitar su frecuencia, según la
  [política de privacidad de Google](https://policies.google.com/privacy).
- **Los usuarios Pro no ven ningún anuncio**, y no se hace ninguna solicitud
  publicitaria para ellos.

## 5. Contribución opcional de códigos (la «red genética»)

Está **desactivada por defecto** y requiere tu consentimiento explícito.

Si la activas y eliges compartir los códigos de un dispositivo, recibimos:

- El protocolo infrarrojo, la dirección y los códigos de botones de ese equipo.
- La marca o el modelo que escribiste, y la versión de la App.
- Un **identificador aleatorio generado en tu dispositivo al instalar** — que
  solo sirve para contar colaboradores distintos, de modo que los códigos se
  validen por mayoría.

Esto **no contiene nombre, correo, número de teléfono, ubicación ni identificador
publicitario**, y no se puede vincular contigo. Puedes desactivar la
contribución cuando quieras en Ajustes.

## 6. Informes de fallos

Se envían informes de fallos anónimos a **Sentry** (región de datos de la UE)
**solo cuando la App falla**. Un informe contiene el error técnico, la versión
de la App y el modelo y la versión del sistema del dispositivo. La información
personal está desactivada explícitamente, y los informes nunca se usan para
publicidad.

## 7. Permisos

- `TRANSMIT_IR` — para emitir señales infrarrojas con el emisor IR de tu
  teléfono. Son pulsos de luz en un solo sentido y no llevan información
  personal.
- `CAMERA` — se usa **solo** cuando eliges «Importar con QR» para escanear un
  código de dispositivo compartido, o «Buscar por modelo» para leer el número de
  modelo en la etiqueta de un equipo. Todo se procesa en tu dispositivo: la foto
  de una etiqueta **se borra en cuanto se lee**, y **no se guarda ni se sube
  ninguna foto ni video**. Puedes negarlo y todo lo demás sigue funcionando.
- **Elegir una foto** — en «Buscar por modelo» también puedes elegir una foto de
  la etiqueta que ya tomaste. El selector de fotos de Android le da a la App solo
  esa foto, sin permiso de almacenamiento; se lee en tu dispositivo, la copia hecha
  para leerla se borra y no se sube nada.
- `INTERNET` — solo se necesita para las funciones opcionales de arriba (cuenta,
  pago, anuncios, informes de fallos, actualizaciones del catálogo). Todas las
  funciones de control funcionan con la red apagada.
- **Detección en la red local** — cuando usas el control por Wi‑Fi, la App busca
  Smart TV en tu propia red (SSDP/DIAL y mDNS), y cuando escribes la dirección IP
  de una TV, comprueba qué puertos de control responden en esa sola dirección
  para reconocer su sistema. Solo se comunica con el equipo que eliges, y ese
  tráfico no sale de tu red doméstica.
- `BLUETOOTH_CONNECT`, `BLUETOOTH_SCAN`, `BLUETOOTH_ADVERTISE` (“Dispositivos
  cercanos”) — se usan **solo** cuando eliges el control Bluetooth o el cursor:
  para encontrar tu TV, emparejarla, hacer visible el teléfono durante el
  emparejamiento y enviarle teclas y movimientos del puntero. La búsqueda está
  declarada “nunca para ubicación”, y los nombres y direcciones que ve no se
  guardan, salvo la dirección de la TV que elijas.
- `ACCESS_FINE_LOCATION` — se pide **solo en Android 11 o anterior**, y solo cuando
  tocas “Buscar dispositivos cercanos”: esas versiones permiten buscar
  dispositivos Bluetooth solo con este permiso. La App nunca lee, guarda ni envía
  tu ubicación. Android 12 y posteriores nunca la piden.
- **Aires Gree** — para controlar un equipo Gree por Wi‑Fi, la App lo encuentra con
  un mensaje de difusión en tu propia red y le habla directamente (cifrado, puerto
  UDP 7000). Nada pasa por ningún servidor.
- `AD_ID` (identificador publicitario) — declarado por Google AdMob para los
  anuncios descritos en la sección 4. Los usuarios Pro no hacen solicitudes
  publicitarias.

La App **no** pide micrófono, contactos, teléfono, SMS ni almacenamiento, y solo
pide la ubicación como se describe arriba (Android 11 o anterior, para la
búsqueda Bluetooth).

## 8. Tus derechos y la eliminación de datos

- **Borrar los datos locales:** desinstala la App o borra sus datos en los
  ajustes de Android.
- **Eliminar tu cuenta y todo lo vinculado** (correo, hash de la contraseña,
  vínculo con la licencia): en la App, abre **Yo → Cuenta → Eliminar la cuenta
  para siempre**. El registro se borra al instante, sin solicitudes ni esperas.
  Una licencia Pro que pagaste se **desvincula, nunca se revoca**: la clave sigue
  funcionando y se puede activar de nuevo. Si no puedes entrar a la App,
  escríbenos a la dirección de abajo desde el correo de la cuenta y la
  borraremos en un plazo de 30 días.
- **Retirar el consentimiento para contribuir códigos:** desactívalo en Ajustes.
  Los códigos que compartiste antes son anónimos y no se pueden vincular contigo.

## 9. Niños

La App es una herramienta para todo público. No está dirigida a niños y no
recopilamos datos de ellos a sabiendas.

## 10. Cambios

Si una versión futura cambia estas prácticas, esta política se actualiza
**antes** de publicar esa versión, y el enlace de la App apunta al texto
revisado.

## 11. Contacto

Preguntas, solicitudes de eliminación de datos o cualquier otra cosa:

**solar.ai.systems@gmail.com**

Solar AI Systems — Argelia
