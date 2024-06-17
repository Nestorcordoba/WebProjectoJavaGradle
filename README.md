# WebProjectoJavaGradle

instalar JDK 

sudo dpkg -i ./jdk-22_linux-x64_bin.deb 

Configurar variable de entorno JAVA en linux

ls -lha /usr/bin/java
ls -lha /etc/alternatives/java
sudo nano /etc/profile
export JAVA_HOME=/usr/lib/jvm/jdk-22-oracle-x64/bin/java
export PATH=${JAVA_HOME}/bin:${PATH}
source /etc/profile
echo $JAVA_HOME

Instalar Gradle

Unzip the distribution zip file in the directory of your choosing, e.g.:

$ mkdir /opt/gradle
$ unzip -d /opt/gradle gradle-8.8-bin.zip
$ ls /opt/gradle/gradle-8.8
LICENSE  NOTICE  bin  getting-started.html  init.d  lib  media

export PATH=$PATH:/opt/gradle/gradle-8.8/bin
