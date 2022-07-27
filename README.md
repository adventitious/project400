# project 400
my project, an app to facilitate decluttering

new title is : Inventory Management System

for people decluttering,
but also for:

people who share a set of resources, 
for example a shed, each worker signs out each object.

a shop can track what is in the store room and 
what is on the shelves.

A shopper, or stock picker, may track the contents of their basket.


Features that are intended to be included

items
containers

qrcodes
barcode

transfer objects from person to person
abstract item, that is, item descriptor
concrete item, an instance of an item, has a quantity

pictures
notifications

search and summary of what items are contained in container

project will have an api, which will require authentification
webserver running python flask app will serve json to api requests.
web server will have single page web app, or similar, 
that makes api requests.
mobile app, uploaded to android play store will make api requests,
in the settings it will be possible to change server

the web app and api will be served through nginx running on a 
ubuntu virtual server.
the installation steps will be fully documented.
the api will be fully documented using possibly through swagger.








