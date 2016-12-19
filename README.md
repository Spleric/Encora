# Encora
A HTML5 Library to bring 'Page' rendering, Template Engine to the client side and accelerate performance.

To get started:


Initate a new variable with the Page Class:

   ```javascript
   page = new Page({
         meta: [{
          title: 'Breaking News Updates, Latest News Headlines, Photos & Videos News',
          description: 'META Description',
        }],

        require: ['account', 'theme'],
        apps: ['radio'],

        style: '',

        header: 'header_generic',
        footer: 'footer_generic'
      });```
