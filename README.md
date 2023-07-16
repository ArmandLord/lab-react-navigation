![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | React Native - React Navigation

## Learning Goals

This exercise allows you to practice and apply the concepts and techniques taught in class.

Upon completion of this exercise, you will be able to:

- Utilizar los componentes básicos de React Native.
- Crear estilos personalizados con StyleSheet.
- Manejar la navegación entre pantallas con React Navigation.
- Utilizar el Stack Navigator para definir las pantallas de nuestra aplicación.
- Pasar data entre pantallas.
- Utilizar TypeScript para tipar las diferentes pantallas de nuestra aplicación.

## Introduction

En este ejercicio vamos a crear un stack navigator con React Navigation que nos permita navegar entre 3 pantallas: una pantalla principal, una pantalla perfil y una pantalla de integrantes del equipo. En la pantalla principal vamos a crear un menú con diferentes botones que nos permitan navegar a las diferentes pantallas de nuestra aplicación. En la pantalla de perfil vamos a mostrar la información de un usuario. En la pantalla de ajustes vamos a mostrar un formulario que nos permita editar la información del usuario. En la pantalla de integrantes del equipo vamos a mostrar una lista de los integrantes del equipo.

## Requirements

- Fork this repo.
- Clone this repo.
- Ejecutar `nvm use` para utilizar la versión de Node que se indica en el fichero `.nvmrc`.

```bash
nvm use
```

- Install the dependencies.

```bash
npm install
```

- Start the project.

```bash
npm run ios
npm run android
```

## Submission

- Upon completion, run the following commands:

```bash
git add .
git commit -m "done"
git push origin master
```

- Create Pull Request so your TAs can check up your work.

## Example

Este es un ejemplo de cómo debería verse la aplicación:

## Instructions

### Iteration 1: Instalar Stack Navigator

- Instalar React Navigation y sus dependencias.
- Instalar Stack Navigator.

### Iteration 2: Crear las carpetas y ficheros necesarios

- Crear una carpeta `src` en la raíz del proyecto.
- Crear una carpeta `screens` dentro de la carpeta `src`.
- Crear una carpeta `components` dentro de la carpeta `src`.
- Crear una carpeta `navigation` dentro de la carpeta `src`.

### Iteration 3: Utilizar NavigationContainer y crear el Stack Navigator

- Importar `NavigationContainer` desde `@react-navigation/native`.
- Importar `createStackNavigator` desde `@react-navigation/stack`.
- Crear la estructura del Stack Navigator.
- Utilizar `NavigationContainer` para envolver el Stack Navigator.
- Utilizar `createStackNavigator` para crear el Stack Navigator.

### Iteration 4: Crear las pantallas de la aplicación y añadirlas al Stack Navigator

- Crear una pantalla principal.
- Crear una pantalla de perfil.
- Crear una pantalla de ajustes.
- Crear una pantalla de integrantes del equipo.
- Añadir las pantallas al Stack Navigator.

### Iteration 5: Crear el menú de la pantalla principal

- Crear un menú con diferentes botones que nos permitan navegar a las diferentes pantallas de nuestra aplicación.

### Iteration 6: Crear la pantalla de perfil

- Crear una pantalla de perfil que muestre la información de un usuario.
- Esta pantalla debe recibir la información del usuario como props. Esta información debe ser un objeto con las siguientes propiedades: `name`, `lastName`, `email`, `phone`, `avatar`.
- Esta pantalla debe mostrar la información del usuario, puedes crear un componente `UserCard` que muestre la información del usuario.
- Esta pantalla debe tener un botón que nos permita navegar a la pantalla principal.

### Iteration 7: Crear la pantalla integrantes del equipo

- Crear una pantalla de integrantes del equipo que muestre una lista de los integrantes del equipo.
- Esta pantalla debe recibir la información de los integrantes del equipo como props. Esta información debe ser un array de objetos con las siguientes propiedades: `name`, `lastName`, `email`, `phone`, `avatar`.
- Esta pantalla debe mostrar la información de los integrantes del equipo, puedes crear un componente `UserCard` que muestre la información de un integrante del equipo.
- Esta pantalla debe tener un botón que nos permita navegar a la pantalla principal.

### Bonus Iteration:

- Crea la interface del `createStackNavigator` para tipar las pantallas de nuestra aplicación.

- Crea la interface del `UserCard` para tipar el componente `UserCard`.

Happy coding! 💙
