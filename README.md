# SimpleAndroid3

## Synopsis
This app uses a to do list to keep track of things for you. It uses a backend service, and maintains a list across multiple platforms. 

## How it works
This app uses [Parse](http://parse.com) (They have some of the bast documentation ever so check it out) API as a backend to store data online, such as users and objects. 

#### Unsurprisingly the action happens in the [mainActivity.java](https://github.com/DavidAwad/SimpleAndroid3/blob/master/app/src/main/java/edu/rutgers/rumad/rumadworkshopthree/completed/MainActivity.java) and [mainActivity.xml](https://github.com/DavidAwad/SimpleAndroid3/blob/master/app/src/main/res/layout/activity_main.xml). So open those in new tabs and look at those for a bit on your own and I'll go into more detail here.

There are some useful things to know about Parse before we get into this. If you're farmiliar with JSON, this is what parse uses to store data. JSON is just a format to store data. Here's an example. 
```JSON
david = {
  'height' : '5.11' ,
  'weight' : '180' ,
  'hooves' : false
} 
```
```JavaScript
console.log( david.height ) ; 
5.11
```
So you can store your information in this convenient format and access it really simply. 

Parse uses entirely JSON objects to manage all of your data and lets you access them however you want. 

Anyway, inside of here we've got some conveient things that parse takes care of for us. Parse will take care of all inserting all our data, and pulling it down when we want to use it for new activities. 


## Contributors 

## Thanks as usual to Shreyas Hirday for the codebase. 
