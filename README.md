# combats

```
javascript:(function(){var iframe=!1;jQuery("iframe").each(function(i,r){void 0!==jQuery(r).attr("name")&&-1!==jQuery(r).attr("name").indexOf("main")&&(iframe=jQuery(r))});var zvs={"zv_1.gif":"%D0%9C%D0%B0%D0%BB%D0%B5%D0%BD%D1%8C%D0%BA%D0%B0%D1%8F","zv_2.gif":"%D0%9C%D0%B0%D0%BB%D0%B5%D0%BD%D1%8C%D0%BA%D0%B0%D1%8F","zv_3.gif":"%D0%9C%D0%B0%D0%BB%D0%B5%D0%BD%D1%8C%D0%BA%D0%B0%D1%8F","zv_4.gif":"%D0%A1%D1%80%D0%B5%D0%B4%D0%BD%D1%8F%D1%8F","zv_5.gif":"%D0%A1%D1%80%D0%B5%D0%B4%D0%BD%D1%8F%D1%8F","zv_6.gif":"%D0%A1%D1%80%D0%B5%D0%B4%D0%BD%D1%8F%D1%8F","zv_7.gif":"%D0%A1%D1%80%D0%B5%D0%B4%D0%BD%D1%8F%D1%8F","zv_8.gif":"%D0%9A%D1%80%D1%83%D0%BF%D0%BD%D0%B0%D1%8F ","zv_9.gif":"%D0%9A%D1%80%D1%83%D0%BF%D0%BD%D0%B0%D1%8F ","zv_10.gif":"%D0%9A%D1%80%D1%83%D0%BF%D0%BD%D0%B0%D1%8F "};if(iframe){var zv=jQuery("h3",iframe.contents()).filter(function(){return"%D0%9B%D0%B5%D1%81"==jQuery(this).text()}).siblings("img").attr("src").split("/").pop();alert(zvs[zv])}})();
```
