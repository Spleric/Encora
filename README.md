# Encora
A HTML5 Library to bring 'Page' rendering, Template Engine to the client side and accelerate performance.

To get started:


Initate a new variable with the Page Class:

   ```javascript
   page = new Page({
         //Set the page META data
         meta: [{
          title: 'Page Title',
          description: 'Page Description',
        }],
        
        
        //Include pre-built or your own custom built apps
        apps: ['radio'],

        //Set the stylesheets or a block of style sheets
        style: 'default',

        //Have a predefined header and footer? Then combine them together!
        header: 'header_generic',
        footer: 'footer_generic'
      });```
