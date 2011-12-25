Capítulo 1 : Instalación de PhoneGap
====================================

En este primer capítulo vas a preparar tu sistema con lo que necesitas para empezar a desarrollar aplicaciones para movil con PhoneGap. Por supuesto el primer paso que vas a ver es el de instalar el mismo PhoneGap para la plataforma que estés utilizando.

Las plataformas que cubre este libro són Microsoft Windows, Apple OSX y Ubuntu Linux tanto si desarrollas para iPhone, Android o BlackBerry siempre que sea posible.

Instalación para Android
------------------------

En caso que quieras desarrollar para Android podrás utililzar tanto Microsoft Windows, Mac OSX o Ubuntu Linux.

### Prerequisitos

Antes de instalar PhoneGap vas a necesitar el SDK Java, Eclipse Classic, el SDK de Android y el plugin ADT Android para Eclipse.

### Instalación del SDK Java

En [http://www.oracle.com/technetwork/java/javase/downloads/index.html](http://www.oracle.com/technetwork/java/javase/downloads/index.html) tienes disponibles versiones del SDK Java para tu plataforma.

#### Instalación para Microsoft Windows

Descarga el instalador para tu plataforma y ejecútala. Una vez haya concluido la instalación ya tendrás disponible el SDK y el Runtime Java en tu ordenador y estarás listo para el siguiente paso.

#### Instalación para Apple OSX

Si tu plataforma es Apple OSX tendrás que descargar el SDK Java desde otro sitio. OSX en su última versión al contrario de las anteriores no incorpora de serie el SDK Java pero Apple tiene a disposición del que lo necesite un sítio donde descargar todo lo necesario en la dirección [http://support.apple.com/kb/DL1421?viewlocale=es_ES](http://support.apple.com/kb/DL1421?viewlocale=es_ES).

#### Instalación para Linux

En caso que tu distribución Linux sea RedHat o Suse en [http://www.oracle.com/technetwork/java/javase/downloads/index.html](http://www.oracle.com/technetwork/java/javase/downloads/index.html) ya tienes disponibles paquetes RPM preparados con lo que la instalación es trivial.

En caso que utillizes Ubuntu Linux sigue los siguientes pasos:

Primero añade el repositorio ejecutando las siguientes líneas desde la interfaz de comandos. Substituye <your_distro> con el nombe de la versión de Ubuntu que estés utilizando.

	sudo add-apt-repository "deb http://archive.canonical.com/ <your_distro> partner"
	sudo apt-get update

Finalmente para instalar ejecuta:

	sudo apt-get install sun-java-jre;sun-java6-bin
  	sudo apt-get install sun-java6-jdk
  	sudo apt-get install sun-java6-plugin sun-java6-fonts

### Instalación de Eclipse Classic

En [http://www.eclipse.org/downloads/](http://www.eclipse.org/downloads/) hay disponibles instaladores tanto para Windows, OSX o Linux de manera que la instalación de Eclipse es trivial. Sólo descarga el fichero para tu plataforma actual, ejecútalo y sigue las instrucciones que te indique.

### Instalación del SDK Android

En [http://developer.android.com/sdk/index.html](http://developer.android.com/sdk/index.html) tienes disponibles versiones para tu plantaforma ya sea Windows, OSX como Linux. Descarga la que se adapte a tu plataforma actual.

#### Instalación para Microsoft Windows

windows

#### Instalación para Apple OSX

osx

#### Instalación para Linux

linux

La última parte de la instalación del SDK de Android es descargar mediante las utilidades que proporciona los componentes y librerias necesarios para completar tu entorno de desarrollo.

Para eso dirígete al directorio tools del SDK y ejecuta:

	android

Figure 8

Aparecerá el diálogo siguiente:

Figure 9

TODO: Componentes a instalar

