## Media Carousel Component

### Overview
Media carousel is a web component for any media object similar to bootstrap's carousel. 

### How to use
 * Run command `bower install --save media-carousel`
 * Add to the beginning of the `head` tag the following:
 
 ```html
 <script src="<path-to-platform.js>"></script>
 <link rel="import" href="<path-to-media-carousel.html>">      
 ```
      
* Add the following code to your html to use the component
      
 ```html
 <media-carousel style="height: <set the height>px">
    <img data-index="1" src="image1.jpg" />
    <img data-index="2" src="image2.jpg" />
 </media-carousel>
 ```

### How to develop
1. Create a folder, e.g. `web-components` and clone the repository into that folder.
2. Run command `bower install` which will bring all dependencies of the component and install them into `web-components`. 
This configuration of `.bowerrc` is intended for reuse of components and recommended by Polymer team.
3. Navigate in terminal to your folder of `web-components` and run `python -m SimpleHTTPServer`, and then navigate to `media-carousel/demo.html`.
4. Install `npm install -g web-component-tester` for testing and run `wct`.
