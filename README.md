# Tech-event-manager (En progreso)

Aplicación para la gestión de eventos.

# Installation

git clone https://github.com/lacasitoscoders/Tech-event-manager.git

composer require laravel/ui

npm install && npm run dev

php artisan key:generate

crear .env (copia y pega del .env.example)

descomentar lineas 24 y 25 del archivo phpunit.xml

npm run watch

## Para iniciar el servidor de desarrollo de Laravel:
php artisan serve

## Contexto del proyecto

Un colectivo de desarrollo de software quiere crear una aplicación web para gestionar sus eventos online como talleres, masterclass o webinars.

Los usuarios podrán ver la descripción de un evento, apuntarse y desapuntarse. Podrán ver la lista de los eventos a los que se han apuntado. El administrador debe tener las herramientas para la gestión (CRUD) de los eventos.

## Requisitos Funcionales:

En portada la aplicación tendrá un slider con las masterclasses destacadas. éstas serán seleccionables por el administrador.
En portada habrá una lista paginada con todos los eventos ordenados del más cercano al más lejano.
Los eventos incluirán como mínimo: título, fecha/hora, número máximo de participantes, descripción y una imagen.
Los eventos pasados se deben mantener en la lista pero identificables como no disponibles.
Los usuarios deberán registrarse para apuntarse a un evento. Una vez apuntados no podran volver a hacerlo.
Al apuntarse a un evento recibirán un email (empresarial - html ) con el link (zoom, meets, etc..) en donde se va a realizar, así como recordando el título del evento, la hora y el día.
Los usuarios podrán ver en una página la lista de los eventos a los que están registrados.
El administrador podrá hacer CRUD de los eventos.
Cuando un evento esté lleno (máximo número de participantes) nadie podrá registrarse.

## Requisitos no funcionales:

La web deberá estar ‘deployed’ aunque esté en desarrollo.
Todos los requisitos y casos de usuario deberán estar testeados (tests de aceptación)
Se deberá usar Laravel.
El envío de el email se deberá hacer usando un sistema de colas.
Para el frontend se deben usar componentes de blade.

## Autor:

Omar Hevia