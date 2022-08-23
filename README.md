# Fuera-Google
Un bash script que se encarga de eliminar las aplicaciones de Google del dispositivo Android. Es recomendable instalar aplicaciones alternativas para hacer uso de los servicios eliminados, como por ejemplo F-Droid.

# Requisitos
Para correr el script es necesario tener instalado ADB, para instalar se ejecuta el siguiente comando:

- Debian/Ubuntu
    ```
    sudo apt install android-tools-adb
    ```
- Fedora/SUSE
    ```
    sudo yum install android-tools
    ```
Es **requerido** que este activada la **depuración de USB** a traves de las opciones de desarollador de su dispositivo android.

Una vez que este activada la depuración USB ejecuta:

```
adb devices 
```
Y debería de aparecer tu dispositivo en la terminal, ejemplo:
```
List of devices attached
********	device
```

Para ejecutarlo hay que ir al directorio del script y ejecutar:

```
./de-google-script
```
# Características
Elimina las siguientes aplicaciones:
- YouTube (Alternativa: NewPipe)
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
