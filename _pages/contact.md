---
permalink: /contact/
title: ""
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

![header](/images/contact_defi.png)

## e-mail 
<a href="mailto:aitor.avila@urv.cat">aitor.avila@urv.cat</a>

## Mailing address
__Universitat Rovira i Virgili__. [Department of Geography](https://www.geografia.urv.cat/ca/)

![logo](/images/URV-Logo6.png)

[Faculty of Tourism and Geography](https://www.ftg.urv.cat/en/)
(_C/Joanot Martorell, 15,
43480, Vila-seca,
Tarragona, Spain_)

<iframe src="https://www.google.com/maps/d/embed?mid=1hJNrhdswmzMeeTN1WHKhwPuA3hnhxFY&ehbc=2E312F" width="640" height="480"></iframe>

__Geographical coordinates__ (_Google Maps_):

> [41°06'09.8"N 1°08'49.2"E](https://www.google.com/maps/place/Facultat+de+Turisme+i+Geografia+-+URV/@41.103352,1.1452928,16.48z/data=!4m5!3m4!1s0x12a159efa0f3c693:0x3ba9bb7077c5ad3!8m2!3d41.1029376!4d1.14701)

> [41.102719, 1.147010](https://www.google.com/maps/place/Facultat+de+Turisme+i+Geografia+-+URV/@41.103352,1.1452928,16.48z/data=!4m5!3m4!1s0x12a159efa0f3c693:0x3ba9bb7077c5ad3!8m2!3d41.1029376!4d1.14701)




<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>Simple else if example</title>
  </head>
  <body>
    <label for="weather">Select the weather type today: </label>
    <select id="weather">
      <option value="">--Make a choice--</option>
      <option value="sunny">Sunny</option>
      <option value="rainy">Rainy</option>
      <option value="snowing">Snowing</option>
      <option value="overcast">Overcast</option>
    </select>

    <p></p>

    <script>
      const select = document.querySelector('select');
      const para = document.querySelector('p');

      select.onchange = setWeather;

      function setWeather() {
        const choice = select.value;

        if(choice === 'sunny') {
          para.textContent = 'It is nice and sunny outside today. Wear shorts! Go to the beach, or the park, and get an ice cream.';
        } else if(choice === 'rainy') {
          para.textContent = 'Rain is falling outside; take a rain coat and a brolly, and don\'t stay out for too long.';
        } else if(choice === 'snowing') {
          para.textContent = 'The snow is coming down — it is freezing! Best to stay in with a cup of hot chocolate, or go build a snowman.';
        } else if(choice === 'overcast') {
          para.textContent = 'It isn\'t raining, but the sky is grey and gloomy; it could turn any minute, so take a rain coat just in case.';
        } else {
          para.textContent = '';
        }
      }
    </script>
  </body>
</html>
