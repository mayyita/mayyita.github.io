---
title: Política de privacidad · Mayyita
---

# Política de privacidad

**Última actualización:** 18 de noviembre de 2026

Mayyita es un bot de Discord. Esta política explica qué datos guarda, para qué, cuánto tiempo y cómo los borras. Respeta los derechos que te da la ley de protección de datos de donde vives.

**Contacto:** el [server de soporte de Mayyita](https://discord.gg/3keaaX6xPU), en el canal #ticket. No damos correo ni otros datos personales.

## Resumen corto

- Guardamos lo mínimo para que el bot funcione en cada server: configuración, sanciones, economía y roles.
- **El texto de los mensajes nunca se guarda en disco.** Vive en memoria hasta 2 horas, solo para el automod, los logs de mensajes editados o borrados y el snipe.
- No vendemos ni compartimos tus datos. No los usamos para entrenar inteligencia artificial.
- Borras tus datos cuando quieras con `,privacy borrar`. **Es gratis siempre.**

## Qué datos guardamos

**De cada server** (los configura su staff):
- Configuración de módulos, mensajes y canales; whitelist; permisos falsos; alias.
- Sanciones (ban, kick, timeout, warn, hardban, jail, tempban) con el ID del usuario, el del moderador, el motivo y la fecha. También las notas del staff.
- Registro de acciones del anti-nuke y copias de la estructura del server (canales, roles y permisos) para poder restaurarlo si lo atacan.
- Economía del server: saldo, banco, registro de movimientos, inventario, tienda, mercado y juegos.
- Contadores sociales (cuántos abrazos le diste a quién, etc.), solo dentro de ese server.
- Roles guardados de cada miembro, para devolvérselos si sale y vuelve. El server puede apagarlo.

**Tuyos, globales** (te siguen a todos los servers):
- Perfil: XP, fondo, marco, título y si quieres salir en el ranking global.
- Logros: cuáles tienes y cuándo los ganaste.
- **Historial de avatares:** hasta 50 avatares tuyos, con la fecha en que el bot los vio. El bot los ve cuando comparte un server contigo, cuando usas un comando suyo, o cuando alguien te menciona o te busca con un comando (`,avatar`, `,banner`, `,ui`, `,names`), también desde la instalación de usuario. Solo es lo que Discord le muestra a cualquier bot: nunca usamos cuentas de usuario ni bases de otros. Se guarda una copia de cada imagen en Cloudflare R2, porque los links viejos de Discord dejan de funcionar. **Cualquiera que tenga el link de una copia puede verla**, igual que tu avatar en Discord. Lo apagas con `,privacy avatares` (eso también lo borra).
- **Historial de nombres:** hasta 50 nombres tuyos (tu nombre de usuario, tu nombre para mostrar y los apodos que usaste en los servers donde está el bot), con la fecha en que el bot los vio. Se anotan en los mismos casos que los avatares; afuera de un server con el bot solo tu nombre de usuario y tu nombre para mostrar. Es global, igual que el de avatares. Lo apagas con `,privacy nombres` (eso también lo borra).
- **Matrimonio:** con quién te casaste (`,marry`) y desde cuándo. Es global: sale en tu perfil en todos los servers. Lo deshaces con `,divorce`.
- **Cumpleaños:** solo si lo pones tú (`,cumple set`), y solo el día y el mes (nunca el año). Sale en tu perfil, y los servers que prendieron el aviso te saludan ese día. Lo borras con `,cumple borrar`.

**Tuyos, en cada server** (no se cruzan entre servers):
- **AFK:** el motivo, desde cuándo y hasta 5 menciones (quién y dónde) mientras no estabas. Se borra solo cuando vuelves a escribir.
- **Recordatorios (`,remind`):** el texto, el canal y la hora. Se borran un día después de avisarte (o antes, con `,remind borrar`).
- **Grupos (gangas, clanes…), si el server los usa:** en qué grupo estás, tu rango y desde cuándo; tu voto en las guerras (si eres staff) y en las encuestas entre grupos. Te sales con `,grupo salir`.
- **Top semanal, si el server lo usa:** una foto por semana de cuánto XP llevas en ese server, para saber cuánto ganaste desde la anterior. Cada semana se reemplaza por la nueva.

**De los servers, no de las personas:**
- **Ranking global de grupos:** cuántos miembros de un server llevan su tag (solo el número), guerras y encuestas ganadas, y cuántos mensajes hubo por día en ese server (solo el total, nunca quién escribió). La actividad se borra a los 30 días.

**Solo en memoria, nunca en disco:**
- Texto de los últimos mensajes de cada canal: hasta 50 por canal y **máximo 2 horas**.
- Para `,editsnipe` y `,reactionsnipe`: los últimos mensajes editados (antes y después) y las reacciones quitadas, hasta 10 por canal y **máximo 2 horas**.
- Tu avatar y tu banner, ya reducidos, hasta 1 hora, para dibujar tu tarjeta de perfil cuando alguien la pide (el banner va de fondo). Si tienes pareja, su avatar sale en chico en tu tarjeta. Se bajan de Discord en ese momento.
- El estado personalizado: solo se mira para el rol de vanity y no se guarda.

**No guardamos:** contraseñas, correos, IP, tu año de nacimiento ni nada de tus mensajes directos.

## Para qué los usamos

- Que funcionen las funciones que el server activa: moderación, seguridad, logs, economía, juegos y perfil.
- Proteger al server de ataques (nukes y raids) y de abuso (spam, cuentas falsas).
- Nada más. No hay publicidad ni perfiles de comportamiento.

## Con quién se comparten

- **Discord:** el bot funciona dentro de Discord; aplica la [política de privacidad de Discord](https://discord.com/privacy).
- **Proveedor del servidor (VPS)** donde corre el bot y su base de datos.
- **Cloudflare R2:** copias de seguridad de la base de datos (privadas) y las copias del historial de avatares.
- **nekos.best:** de ahí salen los GIFs de los comandos sociales. **No se les envía ningún dato tuyo.**
- Los logs que el bot publica en un server los ve el staff de ese server; el server es responsable de lo que hace con ellos.

No vendemos datos a nadie.

## Cuánto tiempo los guardamos

- **Datos de un server:** hasta que el bot sale del server. **A los 30 días** de salir se borran solos, por si lo vuelven a agregar.
- **Tu perfil y logros:** hasta que los borres con `,privacy borrar`.
- **Historial de avatares:** hasta que lo borres (`,clearavatars`, `,privacy avatares` o `,privacy borrar`). Las copias de las imágenes se borran en el momento. Si pasas de 50, se borra el más viejo.
- **Historial de nombres:** hasta que lo borres (`,clearnames`, `,privacy nombres` o `,privacy borrar`). Si pasas de 50, se borra el más viejo.
- **Matrimonio y cumpleaños:** hasta que los borres (`,divorce`, `,cumple borrar` o `,privacy borrar`). Para no saludarte dos veces, cada server anota que ya te saludó ese año.
- **Copias de seguridad:** se guardan **30 días**. Algo que borraste puede seguir en una copia hasta que esa copia vence.
- **Mensajes en memoria:** 2 horas como máximo. Se pierden también si el bot se reinicia.

## Tus derechos y cómo borrar tus datos

- `,privacy`: muestra qué guardamos de ti.
- `,privacy descargar`: te manda un archivo con **todo** lo que guardamos de ti (por DM, o solo para ti con `/privacy`). Una vez por hora. No incluye quién te sancionó, ni quién escribió notas sobre ti, ni el texto de esas notas (son evaluaciones internas de seguridad del staff; solo verás que existen y cuándo).
- `,privacy borraraqui`: borra tus datos **solo en ese server** (roles guardados, economía, contadores sociales, sorteos, AFK, recordatorios y grupos). Tu perfil global, tus avatares y tus nombres (que son globales) quedan.
- `,privacy borrar`: borra tus roles guardados, tu economía en todos los servers, tu perfil global, tus logros, tus contadores sociales, tu historial de avatares (con sus copias), tu historial de nombres, tu matrimonio (la otra persona queda soltera), tu cumpleaños, tus grupos y votos de grupos, y tus mensajes en memoria. Pide confirmación porque no se puede deshacer. **Se conservan** dos cosas: el comprobante de tu premium (si pagaste o booteaste, para no quitarte lo que ya tienes) y tus preferencias de privacidad (tus opt-outs, para no volver a activarte el seguimiento). Si también quieres borrar esas, abre un ticket en el [server de soporte](https://discord.gg/3keaaX6xPU).
- `,privacy avatares`: apaga (y borra) o vuelve a prender tu historial de avatares.
- `,clearavatars`: borra tu historial de avatares. Solo puedes borrar el tuyo.
- `,privacy nombres`: apaga (y borra) o vuelve a prender tu historial de nombres.
- `,clearnames`: borra tu historial de nombres. Solo puedes borrar el tuyo.
- `,estilo privado on`: te saca del ranking global.
- Las **sanciones** (casos de moderación) son registros de seguridad de cada server y no se borran con `,privacy`: se borran cuando se borran los datos de ese server. Si crees que alguna es injusta, habla con el staff del server o abre un ticket en el [server de soporte](https://discord.gg/3keaaX6xPU).
- Para acceso, rectificación, cancelación u oposición (derechos ARCO), usa los comandos de arriba o abre un ticket en el [server de soporte](https://discord.gg/3keaaX6xPU).

## Menores

Discord exige tener al menos 13 años (o la edad mínima de tu país). El bot no busca recolectar datos de menores de esa edad.

## Cambios

Si cambiamos esta política, actualizamos la fecha de arriba y lo avisamos en el server de soporte.
