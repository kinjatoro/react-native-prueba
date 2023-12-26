# COMO CORRER UN PROGRAMA EN REACT NATIVE.
* Instalar Chocolatey.
  1. Abrir el CMD como administrador.
  2. Pegar este comando: `@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "[System.Net.ServicePointManager]::SecurityProtocol = 3072;     iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"`
* Instalar Nodejs-LTS y JDK11 (aunque ya tengas instaladas otras versiones).
  3. Pegar este otro comando: `choco install -y nodejs-lts openjdk11`
* Instalar Android Studio.
  4. Ir a https://developer.android.com/studio (son casi 8GB, tarda bastante).
  5. En el inicio de Android Studio, darle a "more actions" -> SDK Manager -> Show Package Details -> Android 12.0 ("S") -> Android SDK Platform 31 y Intel x86_64 Atom System Image.
  6. Darle a SDK Tools -> Show Package Details -> 31.0.0
  7. Apply -> OK.
  ![image](https://github.com/kinjatoro/react-native-prueba/assets/136925952/8dea243e-b481-47f3-b37f-82a1fbe8c755)
* Configurar variables de entorno.
  8. En el buscador de windows poner "variables de entorno".
  9. Darle a "Variables de entorno..."
  10. En "Variables de usuario" darle a "Nuevo"
  11. Nombre: `ANDROID_HOME`
  12. Valor: `C:\Users\TU USUARIO DE WINDOWS\AppData\Local\Android\Sdk`
  13. "Aceptar"
  14. En "Variables de sistema" buscar "Path" -> "Editar" -> "Nuevo" -> pegar `C:\Users\TU USUARIO DE WINDOWS\AppData\Local\Android\Sdk\platform-tools`
* Instalar React Native.

  
  
---
# TEMPLATES


### Creative Tim
* Argon -> https://github.com/creativetimofficial/argon-react-native (javascript)

* Material -> https://github.com/creativetimofficial/material-kit-react-native (javascript)

* Soft -> https://github.com/creativetimofficial/soft-ui-react-native (typescript)

* Now -> https://github.com/creativetimofficial/now-ui-react-native (javascript)

### Flatlogic
* Starter -> https://github.com/flatlogic/react-native-starter (javascript)

### Instamobile
* Están en la carpeta (son todos javascript)

### Comunidad React Native
* Typescript Template -> https://github.com/react-native-community/react-native-template-typescript (typescript)
---
# CLASE DE MAZZEO
* https://uadeeduar.sharepoint.com/:v:/s/Section_414642/EdpPRDBWhqxMrR4NEXVNt9ABxR4jcS9Rzww95IG9sJ5mtQ?e=3AIfUG
---
# TUTORIALES DE REACT NATIVE
...
