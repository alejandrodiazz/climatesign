# climatesign
Hello! Welcome to our Climate Clock Repository!

The main file we use for creating the numbers and figures we project is "test.html". "index.html" is the website content we host on https://web.mit.edu/climateclock/ 
Most of the other files are ideas or are a part of tests we've done.

"twobanner_static_dynamic.html" was made from test.html to display two banners simultaneously on the harvard Lehman Hall building

If you have any questions please email us at climateclock@mit.edu

# How to build the CLIMATECLOCK widget yourself

### Install prerequisites
Make sure you have [git](https://git-scm.com/downloads) and [yarn](https://yarnpkg.com/en/docs/install) for your system.

### Install the dependencies 
```
yarn install
```
(May have to ``` npm install``` as well)

### Test your build on http://localhost:8080
```
yarn serve
```

### Produce climate-clock-widget/dist/widget-v2.js
```
yarn build
```

Once built, the clock widget can be included on your site using 

```  
<script src="https://yourdomain.com/path/to/widget-v2.js" async></script>
<climate-clock></climate-clock>
```  
