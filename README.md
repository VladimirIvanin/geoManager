# Определение местоположения пользователя

> Для работы нужен localforage (//cdnjs.cloudflare.com/ajax/libs/localforage/1.5.0/localforage.min.js)

```js
var myGeo = new GeoManager({
 succes: function (geoData) {
   console.log(geoData);
 },
 debug: true
});
```
