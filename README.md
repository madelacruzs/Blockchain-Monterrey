# Blockchain-Monterrey
Comunidad enfocada al desarrollo de aplicaciones descentralizadas sobre Blockchain.

## Instalación de IDE

Instalar visual studio code o Sublime Text.

**Visual Studio Code**
1. Instalar visual studio code https://code.visualstudio.com/
2. Instalar Visual Studio extensions. Go into the extensions section, then install these plugins:

  * Solidity
  * Material Icon Theme 

Referencia: [CONFIGURING VISUAL STUDIO CODE FOR ETHEREUM BLOCKCHAIN DEVELOPMENT](https://truffleframework.com/tutorials/configuring-visual-studio-code)


## Installación de herramientas

Las herramientas, librerías y framweworks que se usarán en el taller son los siguientes: `nodejs`, `testrpc` y `truffle`


## Getting started

1) Instalar [nodejs](https://nodejs.org/en/download/). También se pueden usar los [gestores de paquetes](https://nodejs.org/en/download/package-manager/) de cada OS para instalar este framework.
* **Nota:** Si se tiene una versión antigua de nodejs, es posible que los paquetes npm no funcionen (TestRPC requiere node 6.9.1, por ejemplo)

2) Instalar TestRPC. Es posible que se requieran instalar [dependencias adicionales](https://github.com/ethereumjs/testrpc) según el OS en el que se esté trabajando.
Por lo general, la forma de instalarlo es la siguiente:
```
npm install -g ethereumjs-testrpc
```
  Actualización: Instalar  [Ganache CLI](https://github.com/trufflesuite/ganache-cli) 
  ```
  npm install -g ganache-cli
  ```
  * **Nota** TestRPC ahora es Ganache Cli
  
  El flag `-g` es para la instalación global del paquete

3) Instalar [truffle](https://truffleframework.com/docs/getting_started/installation). Sólo debería bastar con el siguiente comando:
```
npm install -g truffle
```
4) Instalar [metamask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn). Metamask es un plugin que se agrega en el navegador web Google Chrome. Metamask provee una billetera electrónica de Ether capaz de interactuar con nuestras Đapps. Debes crear una cuenta ... listo! ya puedes enviar y recibir Ether. Ten en consideración que metamask permite cambiar la red con la que estas trabajando.


Con estas herramientas instaladas, ya estamos en condiciones de desarrollar y probar nuestras Đapps en nuestro entorno de desarrollo local.
