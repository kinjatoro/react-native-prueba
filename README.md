# COMO CORRER UN PROGRAMA EN REACT NATIVE.
### Instalar Chocolatey.
  1. Abrir el CMD como administrador.
  2. Pegar este comando:
    
    @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "[System.Net.ServicePointManager]::SecurityProtocol = 3072;     iex ((New-Object         System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
      
### Instalar Nodejs-LTS y JDK11 (aunque ya estén instaladas otras versiones).
  3. Pegar este otro comando: `choco install -y nodejs-lts openjdk11`
### Instalar Android Studio.
  4. Ir a https://developer.android.com/studio (son casi 8GB, tarda bastante).
  5. En el inicio de Android Studio, darle a "more actions" -> SDK Manager -> Show Package Details -> Android 12.0 ("S") -> **Android SDK Platform 31** y **Intel x86_64 Atom System Image**.
  6. Darle a SDK Tools -> Show Package Details -> **31.0.0**
  7. Apply -> tienen que aparecer los 3 componentes -> OK.

### Configurar variables de entorno.
  8. En el buscador de Windows poner "variables de entorno".
  9. Darle a "Variables de entorno..."
  10. En "Variables de usuario" darle a "Nuevo"
  11. Nombre: `ANDROID_HOME`
  12. Valor: `C:\Users\TU USUARIO DE WINDOWS\AppData\Local\Android\Sdk`
  13. "Aceptar"
  14. En "Variables de sistema" buscar "Path" -> "Editar" -> "Nuevo" -> pegar `C:\Users\TU USUARIO DE WINDOWS\AppData\Local\Android\Sdk\platform-tools`

### Crear un celular para usar de emulador.
  17. Abrir Android Studio
  18. "more actions" -> "Virtual Device Manager"
  19. Puede que aparezca un Pixel_3a con Android 14, ese sería un celular moderno y consume más recursos.
  20. Para emular un celular más viejo, hay que darle al +.
  21. Pixel XL -> Next -> R -> Next -> Finish.
  22. Eliminar el Pixel_3a.
  23. Cerrar Android Studio.

### Crear un proyecto de 0 con React Native (CLI).
  24. Abrir el CMD como administrador.
  25. Ir desde los comandos a la carpeta donde queremos que esté LA CARPETA que contiene todo el proyecto (ojo con eso).
  26. Ejecutamos `npx react-native init NOMBREDELPROYECTO`
  27. Ejecutamos `cd NOMBREDELPROYECTO`
  28. Ejecutamos `code .`
  29. Ejecutamos `npm start` (desde el CMD)
  30. En el VS Code, abrimos una nueva terminal (CTRL shift ñ)
  31. Desde esa nueva terminal ejecutamos `npm run android`. Esta parte tarda bastante y consume mucha CPU.
  32. Si queremos correr el programa en otro momento, solo hay que darle a `npm start` y `npm run android` desde el VS Code.

### Correr un proyecto ya creado.
  1. Abrimos el CMD
  2. Ejecutamos `npx create-expo-app NOMBREDELPROYECTO` **[EXPO]** ó `npx react-native init NOMBREDELPROYECTO` **[CLI]** en la carpeta donde queramos instalar el proyecto.
  3. `cd NOMBREDELPROYECTO`
  4. `npm install --force`
  5. `npx expo start` **[EXPO]** ó `npm start` **[CLI]**
  6. `code .`
  7. Desde la terminal de VS Code: `npm run android`
    

### Probar la app en un celular real.
https://reactnative.dev/docs/running-on-device

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
