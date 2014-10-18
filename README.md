## Media Carousel Component

### Overview
Media carousel is a web component for any media object similar to bootstrap's carousel. 

### How to use
 1. Run command `bower install --save media-carousel`
 2. Add to the beginning of the `head` tag the following:
 
      ```html
        <script src="<path-to-platform.js>"></script>
        <link rel="import" href="<path-to-media-carousel.html>">      
      ```
3. Add the following code to your html to use the component
      
    ```html
    <media-carousel>
      <img data-index="1" src="image1.jpg">
      <img data-index="2" src="image2.jpg">
    </media-carousel>
    ```

### How to develop
1. Create a folder, e.g. `web-components` and clone the repository into that folder.
2. Run command `bower install` which will bring all dependencies of the component and install them into `web-components`. 
This configuration of `.bowerrc` is intended for reuse of components and recommended by Polymer team.
