![](https://miro.medium.com/max/1400/1*zpUEUWiy51-U4cqhi9CIZA.jpeg)


## Hola! 馃憢 Esta es una peque帽a gu铆a para hacer deploy de una app en angular en GithubPages


### Paso 1
Vas a necesitar crear un repositorio en tu github

![](https://res.cloudinary.com/gedgonz/image/upload/v1627790386/1_eznxk7.png)

### Paso 2
Vas a necesitar un proyecto angular, ejecuta el siguiente comando para crear tu proyecto

```js
ng new app-name
```
### Paso 3
Instale Angular CLI gh-pages (https://www.npmjs.com/package/angular-cli-ghpages)

Hay una herramienta a su disposici贸n que puede utilizar para implementar f谩cilmente su aplicaci贸n angular en gh-pages, la herramienta angular-cli-pages.
La herramienta angular-cli-pages se usa como un comando en la CLI angular con el prop贸sito de la implementaci贸n. 

Para instalarlo, ejecutemos este comando en nuestra terminal

```js
npm i angular-cli-ghpages
ng add angular-cli-ghpages
```
#### Nota: 
Este comando instalar谩 angular-cli-ghpages globalmente en su sistema operativo. No es necesario que lo instale de nuevo en caso de que necesite usarlo en el futuro, no es necesario ejecutar nuevamente el primer comando una vez este instalado globalmente.

### Paso 4
Implementar en gh-pages

Despu茅s de crear la aplicaci贸n, ahora puede implementarla en Github Pages usando la herramienta angular-cli-ghpages

Ejecute el siguiente comando en su terminal para implementar la aplicaci贸n, asegurese de escribir correctamente el nombre de su proyecto y que se encuentre dentro de las diagonales //

```js
ng deploy --base-href=/RickAndMorty/
```

### Paso 5
Una vez que desplegu茅 su aplicaci贸n angular dir铆jase a su repositorio y en la sesscion de settings 

![](https://res.cloudinary.com/gedgonz/image/upload/v1627791146/2_alpsoj.png)

de clic en la siguiente secci贸n para obtener la url de la pagina

![](https://res.cloudinary.com/gedgonz/image/upload/v1627791146/3_p96uj6.png)

le mostrara la url y ya podr谩 acceder a ella para ver su app

![](https://res.cloudinary.com/gedgonz/image/upload/v1627791146/4_labnit.png)

![](https://repository-images.githubusercontent.com/381210182/c9263997-0b9e-4fab-ab46-61432263b5d1)

### Nota
GitHubPages dura al rededor de 30 segundos en aplicar los cambios y mostra la app, siga los pasaos a como se inidcan para que no resiva el 404 de github

te dejo el link del proyecto del ejemplo: https://github.com/GedGonz/AppRickAndMorty

Espero esto te ayude en tus implementaciones y pruebas. Saludos!!

