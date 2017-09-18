# Draw.io to Vuejs

### A faster way to build web-app by using draw.io to draw your Vuejs app

## Installation

```
$ npm i -g graph2app-drawio2vuejs
```

## Before starting

Before starting you can read the medium article for a step by step guide:

https://medium.com/@FrancescoZ/from-draw-io-to-vue-js-app-c0f84ede8383

Or watch this little demo:

https://www.youtube.com/watch?v=ktnOmnHjDns&feature=youtu.be

## Quick start
Go to [draw.io](https://www.draw.io) create a new file and use the UML objects in order to create your components tree. Be aware, use only the labelled as an **object** (the fist one).
![alt text](https://github.com/FrancescoSaverioZuppichini/drawIoToVuejs/blob/master/images/object.png?raw=true)

You can use arrows to link the components, the relation parent-children is express by having an arrow from the **children** to the **parent**
![alt text](https://github.com/FrancescoSaverioZuppichini/drawIoToVuejs/blob/develop/images/app_drawio_2.png?raw=true)

If you want to also inclued a file into your component you need to use the specific arrow **use**
![alt text](https://github.com/FrancescoSaverioZuppichini/drawIoToVuejs/blob/develop/images/app_drawio_2.1.png?raw=True)

That means that, for example, the file *Home.vue* will import file *User.vue*.

Once you have finished your application you must export it as XML **not compressed**

Then, to create your components, open the terminal and type

```
drawio2vuejs --xml=<pathToYourXml> --dist=<pathToYourVuejsApp>
```

For help

```
drawio2vuejs --help

```

## Pro Tip
You can fast use the *vue-cli* in order to create an app and then use our program to ovveride *App.vue* and the components folder.

