# Custom Color Wander

Custom Color Wander is an update on Matt's existing library. I found it highly appealing but the code was dysfunctional and a lot of things didn't work. I have cleaned up the bits and made it functional for other applications.

Matt's blog post and more details:

[Generative Art with Node.js and Canvas](http://mattdesl.svbtle.com/generative-art-with-nodejs-and-canvas)

## Live Demo

You can view the algorithm in real-time here:

http://color-wander.surge.sh/

In Chrome, you can right-click the canvas an "Save As" to get the full resolution.

## Outputs

Here are a few examples.

<img src="http://i.imgur.com/VU7G4LX.jpg" width="85%" />  
<img src="http://i.imgur.com/ooYrDUW.jpg" width="85%" />  
<img src="http://i.imgur.com/dTb32La.jpg" width="85%" />  
<img src="http://i.imgur.com/IrZGveh.jpg" width="85%" />  
<img src="http://i.imgur.com/TyI4sQX.jpg" width="85%" />  
<img src="http://i.imgur.com/5QRD3Ps.jpg" width="85%" />  

You can download some of these as lossless PNG [here](https://www.dropbox.com/sh/qhrwaw2rzjqbf5r/AABsYzFc7a4ewWkIJYHHBs85a?dl=0).

## Usage

```sh
git clone https://github.com/PySaqib/custom-color-wander.git
cd color-wander
yarn install
```

To run the browser experience:

```sh
yarn start
```

The image generating renderer wasn't functional so I have excluded it in this repository. However, you can actually send a seed as parameter in this version.

```sh
http://localhost/?seed=123
http://localhost/?seed=456
```

## License

The source code is licensed under MIT, the actual design/visuals/concept/artwork is licensed under [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International](https://creativecommons.org/licenses/by-nc-nd/4.0/). If you need a more specific license for commercial reasons, please open a new issue to discuss it with Matt.
