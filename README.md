# Draw.io to Vuejs

### A faster way to build web-app by using draw.io to draw your Vuejs app

## Installation

```
$ npm i -g graph2app-drawio2vuejs
```

## Before Start

A more detail doc is is coming soon! In the mean time you can read the medium article for a step by step guide:

https://medium.com/@FrancescoZ/from-draw-io-to-vue-js-app-c0f84ede8383

Or watch this little demo:

https://www.youtube.com/watch?v=ktnOmnHjDns&feature=youtu.be

## Quick Start

Create your App as usual with the Vuejs cl

```
vue init ... ...
```

Create your draw.io diagram by going on draw.io and create a new file. To create nodes, select on the left UML > Object and palce them inside the diagram. An arrow from a node to another means that the source node is a children of the target, so it will be create inside the parent's folder. You can add dependencies by using the arrow UML > Use. A dependency will be imported in the source component.

Then you can convert your draw.io diagram 

```
drawio2vuejs --xml=<pathToYourXml> --dist=<pathToYourVuejsApp>
```

For help

```
drawio2vuejs --help

```

