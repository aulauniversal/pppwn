Archivos C++ Compilados Valido para versiones Celular Tablet Tvbox con Arquitectura ARM , MIPS, MIPSEL , X86_64 , CORTEX , AARCH64 ,PI ZERO W, MPCORENOVFP.
REQUESITOS:

**NECESARIO ADAPTADOR USB ETHERNET, OTG O USB-C**

**NECESARIO SER ROOT , VALIDO PARA TODO TIPO DE ROOTEOS**


**NECESARIO TENER TERMUX INSTALADO , AQUI PARA LA ULTIMA VERSIÓN
: https://f-droid.org/repo/com.termux_118.apk***

**ABRIR TERMUX PARA QUE FINALICE LA INSTALACIÓN


**COPIAR ARCHIVOS A LA RAIZ DE TERMUX CON EL GESTOR QUE UTILICES ,
SI NO TIENES NINGUNO TE ACONSEJO ROOT EXPLORER 
DESCARGAR AQUÍ :
https://filehippo.com/es/android/download_root-explorer/4.11.5/***

**COPIAR EN** ***/data/data/com.termux/files/home/***


**CONCEDER PERMISOS DE EJECUCIÓN CON ROOT EXPLORER AL ARCHIVO install**


**INICIAR CON COMANDO** : ***./install***


El script detectara automaticamente la arquitectura entre las diferentes selecciones, si no la encontrase nos saldrá un menú para selección manual
entre las arquitecturas compatibles y disponibles.


Podemos seleccionar cualquier versión de firmware deberemos selecionar numericamente una de ellas 


Nos listará las interfaces de red disponibles el cual deberemos de escribir tal como viene
en el titulo de la lista generada , por ejemplo : eth0 ,en01 ,....


Todo esto generará un archivo que se llamará "run" y nos lo creará ya con la configuración seleccionada anteriormente, listo para ejecutar.

(Este archivo va a contener la configuracion siempre guardada lista para ejecutar , si no cambian las condiciones, (terminal, celular, tablet , USB Ethernet etc...)
Si quisieras volver a reconfigurar por algún motivo de cambio de harware o versión de firmware de ps4 solo tienes que volver a ejecutar el archivo " install " o "install_rasp" 
y se volverá a generar el archivo de ejecución " run ")


**EJECUTAR EL ARCHIVO GENERADO DESPUES DE LA INSTALACIÓN  ***./run***


*****PARA RASPERRY PI Y OTROS SISTEMAS LINUX****


**Deberás copiar los archivos en la carpeta /root/ de la raiz del sistema y una vez copiados ubicarte en ella.


**Se incluye archivo ***install_rasp*** al cual deberás de otorgar permisos de ejecución con el comando : ***sudo chmod 777 install_rasp*** 


*Ejecutar con ./install_rasp y seguir las instrucciones , son los mismos pasos anteriormente mencionados, la diferencia en rasperry es que cambia el directorio
de ejecucion y copia de archivos ya que no vamos a usar termux.



