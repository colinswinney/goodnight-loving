---
layout: page
title: Photos
permalink: /photos/
image: /img/optimized/gnl_stairs_dogs.jpg
weight: 4
band_photos:
  - path: circle-a-trio.jpg
    title: Circle A, Milwaukee, WI
  - path: caves-andyk-colin.jpg
    title: Huntsville Caves
  - path: caves-group.jpg
    title: Huntsville Cave God
  - path: colin-luckenbach.jpg
    title: Luckenbach, TX Locals
  - path: early-mad-planet.jpg
    title: Mad Planet, Milwaukee, WI
  - path: gnl_band_on_a_log.jpg
    title: Band on a Log
  - path: gnl_funny_guys.jpg
    title: Funny Guys
  - path: dogs_on_trail.jpg
    title: Trail Walkin'
  - path: andyh-ryan.jpg
    title: Rhythm Rockers
  - path: colin-andyh.jpg
    title: Live!
  - path: austin-lake-banjo.jpg
    title: Crooked Lake
  - path: gnl_mojo_studio.jpg
    title: Inside Outside Studio, Montebelluna, Italy
  - path: vertical-house-crowd.jpg
    title: Vertcal House, Hunstville, AL
  - path: gnl_zach_red_blur.jpg
    title: Chicago IL, Olde Town Inn?
  - path: gnl-bw-early-logo.jpg
    title: An Early Logo
  - path: baseball-patch.jpg
    title: Baseball
  - path: beer-can-patch.jpg
    title: Beer Can
  - path: harris-accordian.jpg
    title: AndyH Playing an Accordian
  - path: judge-judy-happiness.jpg
    title: Watchin' Our Favorite Show
  - path: kav-singing-2.jpg
    title: AndyK
  - path: kevin-basement.jpg
    title: Kevin's Basement
  - path: luckenbach-post-office.jpg
    title: Luckenbach, TX Post Office
  - path: memphis-kids-show.jpg
    title: Live!
  - path: northwoods.jpg
    title: Goodnight Loving Militia
  - path: rock-n-romp.jpg
    title: Rock N' Romp, Memphis TN
  - path: ryan-haggling.jpg
    title: Ryan Hagglin'
  - path: set-list.jpg
    title: Set List
  - path: sexy-ryan.jpg
    title: Sexy Ryan
  - path: vertical-house-bw.jpg
    title: Vertical House in Black & White
  - path: vertical-house-ryan.jpg
    title: Drummin'
  - path: vertical-house-tweedcaster.jpg
    title: Vertical House Live!
  - path: zach-all-his-glory.jpg
    title: Zach in All His Glory, Vancouver, BC Radio
  - path: zach-colin-afro.jpg
    title: Playground Days
  - path: andys-house-1200.jpg
    title: Loungin' Around
  - path: brewhaus-flyer.jpg
    title: Brewhaus, Milwaukee, WI
  - path: cactus-flyer.jpg
    title: Cactus Club, Milwaukee, WI
  - path: crunchy-frog-flyer.jpg
    title: Crunchy Frog, Green Bay, WI
  - path: flip-out-flyer.jpg
    title: Flip Out Festival, Sydney, Austrailia
  - path: mad-planet-flyer.jpg
    title: Mad Planet, Milwaukee, WI
  - path: miami-flyer.jpg
    title: Goo, Miami, FL
  - path: mint-mint-flyer.jpg
    title: Mint Mint Chocopocalypse, Milwaukee, WI
  - path: orlando-flyer.jpg
    title: Wills Pub, Orlando, FL
  - path: paris-flyer.jpg
    title: La Mecanique, Paris, France
  - path: silent-barn-flyer.jpg
    title: Silent Barn, NYC, NY
  - path: turner-hall-flyer.jpg
    title: Turner Hall, Milwaukee, WI
  - path: vertical-house-flyer.jpg
    title: Vertical House, Huntsville, AL
---
<ul class="photo-ul">
  {% for image in page.band_photos %}
  <li>
    <a href="{{ site.baseurl }}/img/optimized/{{ image.path }}" data-lightbox="photo_page" data-title="{{ image.title }}">
      <img src="{{ site.baseurl }}/img/thumbs/{{ image.path }}" alt="{{ image.title }}">
    </a>
  </li>
  {% endfor %}
</ul>
