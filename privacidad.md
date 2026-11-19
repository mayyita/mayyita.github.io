---
title: Política de privacidad · Mayyita
---

# Política de privacidad

**Última actualización:** 19 de noviembre de 2026

Mayyita es un bot de Discord. Esta política explica qué datos guarda, para qué, cuánto tiempo y cómo los borras. Respeta los derechos que te da la ley de protección de datos de donde vives.

**Contacto:** el [server de soporte de Mayyita](https://discord.gg/3keaaX6xPU), en el canal #ticket. No damos correo ni otros datos personales.

## Resumen corto

- Guardamos lo mínimo para que el bot funcione en cada server: configuración, sanciones, economía y roles.
- **El texto de tus mensajes del chat nunca se guarda en disco.** Vive en memoria unas horas como máximo (ver abajo), solo para el automod, los logs de mensajes editados o borrados y el snipe. `,highlight` lo lee al momento para avisarte y no lo guarda. Lo que sí se guarda es lo que escribes **dentro de un comando** para que funcione: sugerencias, etiquetas, recordatorios, el motivo del AFK y el de un ticket.
- No vendemos ni compartimos tus datos. No los usamos para entrenar inteligencia artificial.
- Borras tus datos cuando quieras con `,privacy borrar`. **Es gratis siempre.**

## Qué datos guardamos

**De cada server** (los configura su staff):
- Configuración de módulos, mensajes y canales; whitelist; permisos falsos; alias.
- Sanciones (ban, kick, timeout, warn, hardban, jail, tempban) con el ID del usuario, el del moderador, el motivo y la fecha. También las notas del staff.
- Apodos fijados por el staff (`,forcenickname`) y roles temporales (`,temprole`), hasta que se quiten o venzan.
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
- **Cuenta de Roblox vinculada:** solo si la vinculas tú (`,roblox link`): tu ID y tu usuario de Roblox, cuándo la vinculaste y cuánto valía tu fit la última vez que se calculó (para el top de fits). Es global: sale en tu perfil en todos los servers, pero el top de fits de cada server solo muestra a sus miembros. Mientras verificas, se guarda el código que pones en tu bio (vence a los 30 min). La quitas con `,roblox unlink`.
- **Last.fm:** solo si lo pones tú (`,fm set`): tu usuario de Last.fm, cuándo lo pusiste y, si los cambias con `,fm react`, tus dos emojis de voto. Es global: `,fm` anda en todos los servers. Lo quitas con `,fm unlink`. Cualquiera puede ver con `,fm @tú` lo que estás escuchando y tu usuario de Last.fm (con link a tu perfil). Si lo conectaste, en `,fm whoknows` del server sales en el top de quién escucha más a un artista.
- **Temporadas:** tus puntos de cada temporada, cuánto sumaste por día (chat, voz, daily, jales y juegos: solo números, nunca el texto), tus insignias y tus pedidos de la tienda de la temporada. Tu nombre sale en el top global de la temporada. Se borra con `,privacy borrar`.
- **Zona horaria:** solo si la pones tú (`,timezone set`): tu zona (por ejemplo "America/Lima") y desde cuándo. Es global: sirve para que `,timezone @tú` diga tu hora en todos los servers. La borras con `,timezone remove`.
- **Cumpleaños:** solo si lo pones tú (`,cumple set`), y solo el día y el mes (nunca el año). Sale en tu perfil, y los servers que prendieron el aviso te saludan ese día. Lo borras con `,cumple borrar`.

**Tuyos, en cada server** (no se cruzan entre servers):
- **AFK:** el motivo, desde cuándo y hasta 5 menciones (quién y dónde) mientras no estabas. Se borra solo cuando vuelves a escribir.
- **Recordatorios (`,remind`):** el texto, el canal y la hora. Se borran un día después de avisarte (o antes, con `,remind borrar`).
- **Grupos (gangas, clanes…), si el server los usa:** en qué grupo estás, tu rango y desde cuándo; tu voto en las guerras (si eres staff) y en las encuestas entre grupos. Te sales con `,grupo salir`.
- **Seen (`,seen`):** la última vez que el bot te vio escribir en ese server (la fecha y el canal, **nunca el texto**). Solo se guarda la última, y quien pregunta solo ve el canal si él también puede verlo. Lo apagas para ti en todos los servers con `,privacy seen` (también lo borra).
- **Highlight (`,highlight`):** las palabras que tú pones (hasta 10 por server) para que el bot te avise por DM si alguien las dice. Solo te avisa de canales que puedes ver. Las quitas con `,highlight remove` o `,highlight clear`.
- **Invites (`,invites`):** en cada server, con qué invitación entraste (el código y quién lo creó), cuándo entraste, cuándo saliste y la fecha de creación de tu cuenta (para no contar cuentas nuevas). También los ajustes que el staff le hizo a tu conteo y los concursos de invites que creaste. Es por server y no se cruza entre servers.
- **Sugerencias (`,suggest`):** el texto de cada sugerencia que mandas, en qué server y cómo quedó. Se borran con `,privacy borraraqui` o `,privacy borrar`.
- **Etiquetas (`,tag`):** el texto de las etiquetas que creas y que eres su autor. Son del server: con `,privacy borrar` quedan, pero ya sin tu nombre.
- **Juegos de a dos (`,tresenraya`, `,conecta4`…):** contra quién jugaste, la apuesta y quién ganó. Las partidas terminadas se borran con `,privacy borrar`.
- **Top semanal, si el server lo usa:** una foto por semana de cuánto XP llevas en ese server, para saber cuánto ganaste desde la anterior. Cada semana se reemplaza por la nueva.

**De los servers, no de las personas:**
- **Ranking global de grupos:** cuántos miembros de un server llevan su tag (solo el número), guerras y encuestas ganadas, y cuántos mensajes hubo por día en ese server (solo el total, nunca quién escribió). La actividad se borra a los 30 días.

**Solo en memoria, nunca en disco:**
- Texto de los últimos mensajes de cada canal: hasta 50 por canal y **máximo 2 horas**.
- Para `,snipe`, `,editsnipe` y `,reactionsnipe`: los últimos mensajes borrados o editados (antes y después) y las reacciones quitadas, hasta 10 por canal y **hasta 2 horas desde que se borraron o editaron** (un mensaje borrado justo antes de cumplir 2 horas puede seguir hasta unas 4 horas desde que se mandó).
- Para `,reactionhistory` (solo el staff): quién puso o quitó qué reacción en un mensaje y cuándo, hasta 300 por canal y **máximo 2 horas**.
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
- **Roblox:** para `,roblox` y `,fit` el bot consulta las APIs públicas de Roblox (perfil, avatar, grupos, catálogo y nombres anteriores), sin iniciar sesión. Solo se les envía el usuario o el ID de Roblox que se busca, **nunca nada de tu Discord**. Lo que responden se guarda en memoria un rato (perfil 10 min, fit 30 min, nombres 1 hora).
- **Last.fm:** para `,fm` (y `,fm top`, `,fm plays` y `,fm whoknows`) el bot le pide a Last.fm lo que escuchas, con el usuario que pusiste. Solo se le envía ese usuario, **nunca nada de tu Discord**. La respuesta queda 30 segundos en memoria.
- **nekos.best:** de ahí salen los GIFs de los comandos sociales. **No se les envía ningún dato tuyo.**
- Los logs que el bot publica en un server los ve el staff de ese server; el server es responsable de lo que hace con ellos.

No vendemos datos a nadie.

## Cuánto tiempo los guardamos

- **Datos de un server:** hasta que el bot sale del server. **A los 30 días** de salir se borran solos, por si lo vuelven a agregar.
- **Tu perfil y logros:** hasta que los borres con `,privacy borrar`.
- **Historial de avatares:** hasta que lo borres (`,clearavatars`, `,privacy avatares` o `,privacy borrar`). `,clearavatars` y `,clearnames` se pueden usar 1 vez cada 15 días (2 cada 3 días si boosteas el server de soporte); `,privacy borrar` y `,privacy avatares`/`nombres` funcionan siempre, al momento. Para eso se guarda cuándo borraste, y `,privacy borrar` también lo borra. Las copias de las imágenes se borran en el momento. Si pasas de 50, se borra el más viejo.
- **Historial de nombres:** hasta que lo borres (`,clearnames`, `,privacy nombres` o `,privacy borrar`). Si pasas de 50, se borra el más viejo.
- **Cuenta de Roblox vinculada:** hasta que la quites (`,roblox unlink` o `,privacy borrar`).
- **Usuario de Last.fm:** hasta que lo quites (`,fm unlink` o `,privacy borrar`).
- **Zona horaria:** hasta que la quites (`,timezone remove` o `,privacy borrar`).
- **Seen:** solo la última vez, que se reemplaza cada vez que escribes. Hasta que lo apagues (`,privacy seen`), lo borres (`,privacy borraraqui` o `,privacy borrar`) o el bot salga del server.
- **Palabras de highlight:** hasta que las quites (`,highlight remove`, `,highlight clear`, `,privacy borraraqui` o `,privacy borrar`).
- **Invites:** mientras sigas en el server. Al salir, **90 días** (para contar quién se fue) y después se borra.
- **Matrimonio y cumpleaños:** hasta que los borres (`,divorce`, `,cumple borrar` o `,privacy borrar`). Para no saludarte dos veces, cada server anota que ya te saludó ese año.
- **Copias de seguridad:** se guardan **30 días**. Algo que borraste puede seguir en una copia hasta que esa copia vence.
- **Mensajes en memoria:** 2 horas como máximo. Se pierden también si el bot se reinicia.

## Tus derechos y cómo borrar tus datos

- `,privacy`: muestra qué guardamos de ti.
- `,privacy descargar`: te manda un archivo con **todo** lo que guardamos de ti (por DM, o solo para ti con `/privacy`). Una vez por hora. No incluye quién te sancionó, ni quién escribió notas sobre ti, ni el texto de esas notas (son evaluaciones internas de seguridad del staff; solo verás que existen y cuándo).
- `,privacy borraraqui`: borra tus datos **solo en ese server** (roles guardados, economía, contadores sociales, sorteos, AFK, recordatorios, grupos, seen, highlight, invites y sugerencias; tus etiquetas quedan sin tu nombre y quienes invitaste quedan como "no se sabe"). Tu perfil global, tus avatares y tus nombres (que son globales) quedan.
- `,privacy borrar`: borra tus roles guardados, tu economía en todos los servers, tu perfil global, tus logros, tus contadores sociales, tu historial de avatares (con sus copias), tu historial de nombres, tu cuenta de Roblox vinculada, tu usuario de Last.fm, tu seen, tus palabras de highlight y tus invites en todos los servers, tu zona horaria, tus sugerencias, tus sorteos, tu top semanal, tu rol de booster, tus partidas de a dos (y tu nombre de autor en las etiquetas), tu matrimonio (la otra persona queda soltera), tu cumpleaños, tus grupos y votos de grupos, y tus mensajes en memoria. Pide confirmación porque no se puede deshacer. **Se conservan** dos cosas: el comprobante de tu premium (si pagaste o booteaste, para no quitarte lo que ya tienes) y tus preferencias de privacidad (tus opt-outs, para no volver a activarte el seguimiento). Si también quieres borrar esas, abre un ticket en el [server de soporte](https://discord.gg/3keaaX6xPU).
- `,privacy avatares`: apaga (y borra) o vuelve a prender tu historial de avatares.
- `,clearavatars`: borra tu historial de avatares. Solo puedes borrar el tuyo.
- `,privacy nombres`: apaga (y borra) o vuelve a prender tu historial de nombres.
- `,clearnames`: borra tu historial de nombres. Solo puedes borrar el tuyo.
- `,privacy seen`: apaga (y borra) o vuelve a prender tu seen en todos los servers.
- `,estilo privado on`: te saca del ranking global.
- Las **sanciones** (casos de moderación) son registros de seguridad de cada server y no se borran con `,privacy`: se borran cuando se borran los datos de ese server. Si crees que alguna es injusta, habla con el staff del server o abre un ticket en el [server de soporte](https://discord.gg/3keaaX6xPU).
- Para acceso, rectificación, cancelación u oposición (derechos ARCO), usa los comandos de arriba o abre un ticket en el [server de soporte](https://discord.gg/3keaaX6xPU).

## Menores

Discord exige tener al menos 13 años (o la edad mínima de tu país). El bot no busca recolectar datos de menores de esa edad.

## Cambios

Si cambiamos esta política, actualizamos la fecha de arriba y lo avisamos en el server de soporte.
