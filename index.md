---
title: Hatay Benim Şahsi Meselem
layout: home
description: >-
  Hatay’ın orta ve uzun vadede ihtiyacı olan hali haızrda başlamış ve
  başlatılması gereken çalışmaları listelediğimiz bir
intro_image: images/illustrations/pointing.svg
intro_image_absolute: true
intro_image_hide_on_mobile: true
show_call_box: true
published: true
location:
  latitude: 51.5285582
  longitude: -0.2416807
---

# Hatay Benim Şahsi Meselem

{% if page.locations %} 
<img src="http://maps.googleapis.com/maps/api/staticmap?{% for location in page.locations %}{% if forloop.first %}center={{location}}&markers=color:blue%7C{{location}}{% else %}&markers=color:blue%7C{{location}}{% endif %}{% endfor %}&zoom={% if page.zoom %}{{page.zoom}}{% else %}13{% endif %}&size=300x200&scale=2&sensor=false&visual_refresh=true" alt="">
{% endif %}


Hatay'ın orta ve uzun vadede ihtiyacı olan hali hazırda başlamış ve başlatılması planlanan çalışmaları listelediğimiz bir platform. 



[Hatay Yarım Dağıtım Merkezleri Kayıt Formu](https://forms.gle/6dU1vnW2PV9jeP7KA)
