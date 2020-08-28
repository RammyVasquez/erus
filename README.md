# erus

Test de Ionic funcionando a través de un API
Login y Registro de Usuarios a tarvés de Fire Base


### Pre-requisitos 📋

_Que cosas necesitas para instalar el software y como instalarlas_

```Tener una base de datos en firebase con permisos de crear con correos

``` (En caso de no tener Ionic instalado)
instalar node.js 

instalar ionic a traves de  npm :

  npm install -g @ionic/cli
  
```

### Instalación 🔧


```
Correr el siguiente comando:

  npm install
  
`` Firebase**
 Ingresar la informacion de sign in- method habilitar el proveedor de correo
  (despues tegenera una variable, se copia eso y se pega en el proyecto)
  src/environments/environments.ts
    ejemplo:
        export const environment = {
        production: false,
        firebaseConfig: {
          apiKey: "AIzaSyBUTQCTxcNV3XGdAxjKNrewF-O1Kl-V_KE",
          authDomain: "erus-9dbcd.firebaseapp.com",
          databaseURL: "https://erus-9dbcd.firebaseio.com",
          projectId: "erus-9dbcd",
          storageBucket: "erus-9dbcd.appspot.com",
          messagingSenderId: "10923515945",
          appId: "1:10923515945:web:934c9cb72f624dc257fc38",
          measurementId: "G-M90TN18PBG"
        }
      };


``
para visualizar correr el sig. codigo:

  ionioc serve ó ionic lab
  
```

## Construido con 🛠️

Ionic
API
Angular
FireBase

## Autores ✒️

* **Ramses Urquijo** - *Trabajo Inicial* - [ramsesurquijo](https://github.com/RammyVasquez)

## Licencia 📄

Este proyecto está bajo la Licencia (rammy1) 

## Expresiones de Gratitud 🎁

*Espero ser de ayuda!



---
⌨️ con ❤️ por [RamsesUrquijo](https://github.com/RammyVasquez) 😊
