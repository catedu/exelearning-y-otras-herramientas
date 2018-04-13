
# Quandary

Para Quandary, podemos integrar de dos formas:

- Si la actividad está colgada en internet, y la insertamos con el idevice "Sitio web externo" o con el botón sitio web embebido y eligiendo tipo "iframe". Similar a como hemos hecho para ThatQuiz
- Si la actividad la tenemos en local (en nuestro ordenador), podemos embeber utilizando el botón embeber en HTML
![](img/boton_embeb.jpg) En este caso, debemos pegar el código:

```html
<iframe src="carpeta/index.html" frameborder="0" height="600" scrolling="auto" width="800"></iframe>
```

sutituyendo la ruta de la actividad (carpeta/index.html) por la realidad. Veamos cómo:

 <object data="http://aularagon.catedu.es/materialesaularagon2013/herramelabor/tm4/exe_quandary.swf" height="600" type="application/x-shockwave-flash" width="800"><param name="src" value="http://aularagon.catedu.es/materialesaularagon2013/herramelabor/tm4/exe_quandary.swf"/></object>

 

