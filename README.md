# AOSP Resurrected Cooperve

Esta basado en la ROM AOSP GB de Spacecaker, con varias mejoras entre otras...

## Recomendaciones para mejor uso y rendimiento de AOSP Resurrected Cooperve

+ Utilizar el booster adrenaline engine, la version basada en Cyanogenmod 7.2, es opcional, de todos modos la rom es fluida.

+ No modificar el sistema instalandole varios boosters a la vez, cambiando valores raros al build.prop o se ganaran un bootloop.

+ En el link2sd ya integrado en la rom, si ya particionaron la tarjeta microsd con cwm u otro, darle a recrear script de montaje.

  La primera vez saldra un dialogo de sistema de ficheros a usar al iniciar link2sd, seleccionar ext3 o fat32, reiniciar.

+ No instalar aplicaciones que consuman mucha ram "facebook para android", favor de usar fb lite para el ACE, u otras de ese tipo

  no hay problema con WhatsApp, Telegram u otras normales.

+ Si usas Telegram por temas de arquitectura del Galaxy Ace "armv6" se puede usar hasta la version 3.6.1 sin problemas.

+ Si usas Plus Messenger, extraoficialmente hasta la 3.9.0.3 (build universal) se puede usar. Por tema de ser 2.3 y armv6

+ En las opciones de Link2sd al instalar una aplicacion nueva, opcion de enlaze automatico a la SD, si es lo quieres asi.

###Link de la rom 

+ Version actual 1.2.2

+ http://ur1.ca/ps74s

+ Kernel

+ http://ur1.ca/prolp

+ CWM no instalable "por si usas recovery stock y quieres instalar el kernel de bieltv3": http://ur1.ca/pwv31

+ Gapps minimas "se va el error 492"

+ http://www.mediafire.com/download/ulepgpzjrmfjqrb/SlimGappsbymathm2013

## Mejoras

+ Mejoras en la gestion de ram, añadido un gestor de tareas portado de Alternative ROM by Gabo.

+ Mas duracion de bateria sobretodo en sueño profundo "deep sleep", con varios trucos en el build.prop.

+ Recuperada la capacidad de conectarse en zonas y/o porque lo quieres asi a Edge, con su E funcionando normal (antes no se podia).

+ Sacada la Galeria 3D de AOSP, ya que es muy lenta da lags y/o tirones con muchas imagenes, en cambio se usa quickpic

+ Zeam Launcher por defecto "el launcher mas ligero de android" existente.

+ Solucionado el tema de link2sd y conflicto de script de montaje de la particion sdext2, antes la rom tenia un script que causaba conflictos.

+ Arreglado un bug con WhatsApp en el tema de audio de voz, y/o llamadas voip, el primero se entrecortara un poco aun.

  Si se escucha un audio enviado no hay ningun problema.

+ Soporta init.d como la rom base original.

+ Recuperado el grabador de sonido, el de AOSP ni funcionaba bien, añadido algunas utilidades de Cyanogenmod 7.2.

+ Ya integrado el fix de la camara, se puede sacar fotografias con flash sin problemas.

+ Si eres prepago es compatible con el paquete de redes sociales de Claro o cualquier operadora, "no funciona con la app de twitter" en esta ROM.

+ Limpieza general...

+ No hay estadisticas de paquetes negativos si estas conectado a una red movil, como pasa en roms basadas en CM 7.2.

+ Se ha integrado aScreenshot, ya que la rom base ni era capaz de sacar capturas de pantalla.

+ Se elimino play store por temas del error 492, pero se pasa link de las gapps minimas que quitan el error.

+ Soporta también Intext2+ (montar sdext2 como interna)

## BUGS

+ No hay flash de la camara cuando se graba videos.

+ El tethering wifi no funciona.

+ Whastapp hara falsas estadisticas de bateria, si se envia mensajes de voz y subiria a niveles absurdos "50% de uso de bateria" en las estadisticas de uso de bateria, nativa de android. No afecta en el consumo de bateria para nada.

+ A veces lo mismo le pasa a Telegram, pero no se entrecorta los mensajes enviados.

+ Ese bug tambien esta presente hasta en la misma rom stock.

## Instalacion

+ Si ya tenias una rom instalada basada en cyanogenmod 7.2, en el menu recovery "boton encendido + boton de volumen arriba + boton central"

  Apretar esos 3 botones a la vez por 4 a 5 segundos, hasta que el logo parpadee y se reinicie otra vez.

+ Wipe data/cache, Wipe cache, advanced wipe dalvik cache, en mounts and storage, format /system, /data y /cache, ¡no sdcard!.

+ Una vez hecho eso en el menu recovery seleccionar install zip from sdcard, dar a choose zip from sdcard, seleccionar la .zip copiada a la SD, darle yes.

+ Reboot system now, "tardara un poco al primer inicio la rom", no asustarse.

### Si estas en rom Stock

+ Asumo que lo tienes ya rooteado.

+ Lo mismo para acceder al menu recovery que lo anterior.

+ Usar el CWM que no se instala, en el recovery stock, dale a update from sdcard, instalar el CWM, despues...

+ Wipe data/cache, Wipe cache, install zip from sdcard, instalar el kernel 3.0 de Bieltv3, darle yes, en advanced, reboot recovery.

+ Wipe data/cache, Wipe cache, en mount and storage, format /system, /data, /cache, ¡no a la sdcard!, advanced wipe dalvik cache

  Esto hara que el sistema de la EEPROM, sea ext4, no rfs como en la stock, ya no se necesita el ext4_formater como en los inicios de CM 7.2.

+ Una vez hecho eso en el menu recovery, seleccionar install zip from sdcard, dar a choose zip from sdcard, seleccionar la .zip copiada a la SD, darle yes.

+ Reboot system now, "tardara un poco al primer inicio la rom", no asustarse.

### Capturas de pantalla

+ Las aplicaciones que aparecen, no todas vienen instalada por defecto, obviamente.

+ http://i.imgur.com/bSxyBgn.jpg

+ http://i.imgur.com/dorr4Xr.jpg

+ http://i.imgur.com/nzXzxre.jpg
