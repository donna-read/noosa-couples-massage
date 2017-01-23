---
layout: default
title: Contact
date: 2016-11-29 13:32:10 +1100
permalink: /contact
---

<section>
  <div class="bg">
    <h1>Contact</h1>
    <article>
      <p>For an appointment please call me on: <a href="tel:0402473804">0402 473 804</a></p>
      <p>For all other enquiries you can reach me at <a href="mailto:donna@massagebydonnaread.com.au">donna@massagebydonnaread.com.au</a></p>
      <p>Open 7 days, 7am to 7pm.</p>
      <p>My studio is located at:</p>
      <p>38 Webya St<br>Sunshine Beach QLD 4567</p>
      <div id="map_canvas"></div>
      <p><a href="http://maps.google.com.au/maps?q=38+Weyba+St+Sunshine+Beach+4567,+Queensland&hl=en&ll=-26.40557,153.10569&z=17">view larger map</a></p>
      <p>Look forward to seeing you soon!</p>
    </article>
  </div>
</section>

<script>
  var map, latlng, marker;
  function mapReady() {
    latlng = new google.maps.LatLng( -26.40557, 153.10569 );
    map = new google.maps.Map(document.getElementById('map_canvas'), {
      center: latlng,
      zoom: 13,
      mapTypeId: google.maps.MapTypeId.ROADMAP
    });
    marker = new google.maps.Marker({
      position: latlng,
      map: map,
      title: "38 Webya St, Sunshine Beach QLD 4567"
    });
  }
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyB1p18emCkiJXwYlLde4fJoPa7c8j2Q4CM&callback=mapReady" async defer></script>
