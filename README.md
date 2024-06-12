Archivos C++ Compilados Valido para versiones Celular Tablet Tvbox con Arquitectura ARM , MIPS, MIPSEL , X86_64 , CORTEX , AARCH64 ,PI ZERO W, MPCORENOVFP.
REQUESITOS:

**-NECESARIO ADAPTADOR USB ETHERNET, OTG O USB-C**

**-NECESARIO SER ROOT , VALIDO PARA TODO TIPO DE ROOTEOS**


**-NECESARIO TENER TERMUX INSTALADO , AQUI PARA LA ULTIMA VERSIÓN
: https://f-droid.org/repo/com.termux_118.apk***

**-ABRIR TERMUX PARA QUE FINALICE LA INSTALACIÓN**


**-COPIAR ARCHIVOS A LA RAIZ DE TERMUX CON EL GESTOR QUE UTILICES ,
SI NO TIENES NINGUNO TE ACONSEJO ROOT EXPLORER 
DESCARGAR AQUÍ :
https://filehippo.com/es/android/download_root-explorer/4.11.5/***

**-COPIAR ARCHIVOS "install_termux" Y CARPETAS "/cpu/ y /stages/"  EN LA SIGUIENTE UBICACIÓN** ***/data/data/com.termux/files/home/***


**-CONCEDER PERMISOS DE EJECUCIÓN CON ROOT EXPLORER AL ARCHIVO install**

![Snapshot_2](https://github.com/aulauniversal/pppwn-Tvbox-Rasp.Zero-Android-FULL-Version/assets/168633732/2b66da44-ca53-49ef-ade5-f43f76dd195a)


**-INICIAR CON COMANDO** : ***./install_termux***

![Snapshot_8](https://github.com/aulauniversal/pppwn-Tvbox-Rasp.Zero-Android-FULL-Version/assets/168633732/75e39160-3107-4940-b54c-10cf91905629)


El script detectara automaticamente la arquitectura entre las diferentes selecciones, si no la encontrase nos saldrá un menú para selección manual
entre las arquitecturas compatibles y disponibles.

Nos listará las interfaces de red disponibles el cual deberemos de escribir tal como viene
en el titulo de la lista generada , por ejemplo : eth0 ,en01 ,....

![Snapshot_3](https://github.com/aulauniversal/pppwn-Tvbox-Rasp.Zero-Android-FULL-Version/assets/168633732/6ed13cc5-e862-4905-9875-2b0b70f6cc75)


Podemos seleccionar cualquier versión de firmware, deberemos selecionar numericamente una de ellas 

![Snapshot_4](https://github.com/aulauniversal/pppwn-Tvbox-Rasp.Zero-Android-FULL-Version/assets/168633732/2a22312c-895e-4c6f-8b44-7feb41f01bf4)

Esto generará un archivo que se llamará "run" y nos lo creará ya con la configuración seleccionada anteriormente, listo para ejecutar.

Este archivo va a contener la configuracion siempre guardada lista para ejecutar , si no cambian las condiciones, (terminal, celular, tablet , USB Ethernet etc...)
Si quisieras volver a reconfigurar por algún motivo de cambio de harware o versión de firmware de ps4 solo tienes que volver a ejecutar el archivo " install_termux " o "install_notermux" 
y se volverá a generar el archivo de ejecución " run "


**EJECUTAR EL ARCHIVO GENERADO DESPUES DE LA INSTALACIÓN**  ***./run***
![Snapshot_6](https://github.com/aulauniversal/pppwn-Tvbox-Rasp.Zero-Android-FULL-Version/assets/168633732/2d2e74d8-70a1-464c-8b3d-eacf41f6c752)

![Snapshot_7](https://github.com/aulauniversal/pppwn-Tvbox-Rasp.Zero-Android-FULL-Version/assets/168633732/c05641ff-aa59-4313-a426-4cfdb13707b7)

*****PARA RASPERRY PI Y OTROS SISTEMAS LINUX****


**-Copiar archivo "install_notermux" Y carpetas "/cpu/ y /stages/"  en la siguiente ubicación** ***/root/***


**-Ubícate en la carpeta anterieormente mencionada /root/**


**-Otorgar permisos de ejecución con el comando** : ***sudo chmod 777 install_notermux*** 


**-Ejecutar con ***./install_notermux*** y seguir las instrucciones** 

(si no actúa la selección manual quiere decir que lo a detectado automaticamente
, son los mismos pasos anteriormente mencionados, la diferencia en rasperry y otros sistemas linux es el cambio de directorio
de ejecucion y copia de archivos ya que no vamos a usar termux.)



