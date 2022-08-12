# Fuera-Google
Un bash script que se encarga de eliminar las aplicaciones de Google del dispositivo Android. Es recomendable instalar aplicaciones alternativas para hacer uso de los servicion eliminados, a ser preferible a traves de la F-Droid.

# Requisitos
Para correr el script es cesario tener instalado ADB, para instalar se ejecuta el siguiente comando:

```java
sudo apt install adb 
```
Decir que es **requerido** que este activada la **depuracion de USB** a traves de las opciones de desarollador.

Una vez que esta activada ejecuta:

```java
adb devices 
```
Y deveria de aparecer tu dispositivo en la terminal.

Para ejecutarlo hay que ir al directorio del script y ejecutar:

```java
./de-google-script
```
# Caracteristicas
Elimina las siguientes aplicaciones:

- YouTube. (Alternativa: NewPipe)
- Gmail
- Keep
- Play Store (Alternativa: Aurora Store)
- Calendario
- Mapas (Recomendado utilizar la version web)
- Bienestar Digial
- Drive
- Contactos (Alternativa: Simple Contacts)
- App de Google
- Fotos (Alternativa: Simple Gallery)
- Mensajes (Alternativa: Simple SMS)
- Telefono (Alternativa: Simple Dialer)
- Archivos
- Asistente
- Google chrome
- Google Pay
