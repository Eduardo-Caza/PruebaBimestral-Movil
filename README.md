# Prueba Bimestral Desarrollo de Aplicaciónes Móviles 📝

> **Estudiante**: Eduardo Caza

Para el desarrollo de la prueba se tomo de referencia los trabajos desarrollados en clase, deberes y trabajos grupales 

Contenido : Una aplicacion que consume dos Api's y guarda estas mismas en Firebase

> **Descarga la apk**: [Descargar archivo](https://github.com/Eduardo-Caza/PruebaBimestral-Movil/blob/master/PruebaBimestral-ECaza.apk)

---

## Capturas de Pantalla 📸

### Comprobacion de Funcionalidad de la APK

![image](https://github.com/user-attachments/assets/3589a57d-decf-4bfa-9684-0e9edaf8c521)

![image](https://github.com/user-attachments/assets/697b1284-9fe9-48bc-864f-9b24b5e83c0c)

![image](https://github.com/user-attachments/assets/d08bfc3f-471a-4630-9db1-740e7b27be1a)


### Interfaz Principal

![image](https://github.com/user-attachments/assets/a334bdcd-eb81-42d9-9e44-f19ef8513cfc)

### FireStore DataBase

![image](https://github.com/user-attachments/assets/1c87fb64-9898-4bd6-aa7f-74c14b4922db)
---

## Pasos a Seguir para configurar el Proyecto en Ionic 💻

1. Para crear el proyecto en IONIC usaremos el siguiente comando
   ```bash
   ionic start APLICACION blank --type=angular
2. Dentro de nuestro proyecto de ionic
   ```bash
   ionic g service services
3. Y de paso instalamos los respectivos capacitadores 
   ```bash
   npm i @angular/fire
   npm i @ionic/pwa-elements
4. Y integramos firebase en nuestro proyecto 
   ```bash
   ng add @angular/fire

## Pasos a Seguir para construir nuestra apk en android o en IOS💻

1. Añadimos el capacitor de android y de IOS
   ```bash
   ionic cap add android
   ionic cap add ios
2. Luego de añadir los capacitores construimos nuestra app
   ```bash
   ionic build
3. Comprobamos en android studio abrimos la apk
   ```bash
   ionic cap open android
4. O miramos en nuestro ordenador con ionic serve
   ```bash
   ionic serve
5. Ejecucion del Programa:

![image](https://github.com/user-attachments/assets/cfcf7eac-77f8-4e1f-bec5-79c7c514282e)

