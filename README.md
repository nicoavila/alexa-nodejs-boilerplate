# Alexa Skill NodeJS Boilerplate con Serverless Framework
> Boilerplate para construir una Alexa Skill utilizando **Serverless Framework** con **NodeJS**

## Artículo

![Alexa Skill NodeJS Portada](https://nicoavila.s3.us-west-2.amazonaws.com/articulos/21_01construyendo-skill-alexa-serverless-nodejs.png)

¿Prefieres una guía detallada?  
En el [Medium de NodersJS](https://medium.com/noders) está publicado un artículo titulado **Construyendo una Skill de Alexa con Serverless Framework y NodeJS**. Esta guía paso a paso te ayudará a crear tu propio skill de Alexa con este boilerplate :smile:

## ¿Qué es Alexa?
> Fuente original: Definición extraída desde [Wikipedia](https://es.wikipedia.org/wiki/Amazon_Alexa)

_Alexa es un asistente virtual desarrollado por Amazon.  
Puede responder preguntas, reproducir música de servicios como Spotify, Apple Music, TuneIn y Amazon Music, crear listas de comprobación, establecer alarmas o temporizadores, reproducir podcasts y audiolibros, controlar dispositivos inteligentes, proveer información en tiempo real del clima, tráfico y brindar resúmenes de noticias, entre otros.  
Actualmente, Alexa está disponible en inglés, alemán, japonés, francés, italiano y español._

## ¿Qué es una skill?
> Fuente original: Definición extraída desde [Wikipedia](https://es.wikipedia.org/wiki/Amazon_Alexa)

_Las skills de Alexa son el equivalente a las aplicaciones de los smartphones. Éstas añaden nuevas funcionalidades al asistente inteligente de Amazon, y están disponibles en la tienda de Skills.  
En ella, se pueden encontrar skills de diferentes categorías. Entre las categorías de Skills disponibles se encuentran: Skills de juegos y curiosidades, música, noticias, estilo de vida, negocios y finanzas, salud, entretenimiento, comida y bebidas y hogar.  
Al activar la skill desde la tienda, estará disponible en todos los dispositivos Alexa vinculados a tu cuenta. Algunas Skills ofrecen compras dentro de la aplicación (In-App Purchases)_

## ¿Qué hace este proyecto?
Este proyecto pretende entregar una estructura prefabricada para construir [Alexa Custom Skills](https://developer.amazon.com/docs/custom-skills/understanding-custom-skills.html) de forma más rápida y eficiente utilizando Serverless Framework, NodeJS y el modelo de la skill versionado con YAML.

### Características

* :factory: Estructura lista! Solo debes agregar tus intents y slots favoritos.
* :computer: Utiliza Serverless Framework para realizar el deploy de la skill en sencillos pasos.
* :microphone: El modelo de interacción se encuentra versionado en un archivo. Modifica el archivo para reflejar los cambios en tu skill.


## Estructura de proyecto: Archivos importantes
* ```environment.json```: Lorem 
* ```alexa-model.yml```: Lorem
* ```serverless.yml```: Lorem
* ```handler.js```: Lorem

## Pre-requisitos
1. [Node Version Manager](https://github.com/nvm-sh/nvm)
2. Cuenta en [Amazon Web Services](https://console.aws.amazon.com/console/home)
3. Cuenta en [Amazon Developers](https://developer.amazon.com/)

## Configuración

### Amazon Web Services: AWS IAM Credentials
1. El primer paso es crear un

### Amazon Developers: Configuración de Security Profile
3. Obtener tu **Amazon Vendor ID** [aquí](https://developer.amazon.com/settings/console/mycid)

### Serverless: Configuración de credenciales AWS
1. Lorem

## Pasos
1. Clonar el repositorio en tu computador.
2. Instalar [Serverless Framework](https://serverless.com/) con `npm installl -g serverless`