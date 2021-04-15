# climatesign
HTML Pages to display on MIT Building for Climate Action
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
