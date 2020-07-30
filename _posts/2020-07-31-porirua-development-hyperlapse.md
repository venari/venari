---
author: Leigh
layout: post
---

This has been a fun project to work on with [Porirua Development][porirua-development] over the last 16 months, capturing the enormous progress that has taken place at Castor Crescent in Porirua, transforming it from a neglected field into 53 new homes.

By flying a predefined path multiple times, and then applying some fairly detailed post-processing, we are able to merge the video captures from different dates, illustrating the changes to the site over several months or years.

This project involved:

* 8 site visits capturing video
* 30+ hours editing and post-processing, and further refining and optimising method


[porirua-development]: https://poriruadevelopment.co.nz/

## Before and After
These two photospheres illustrate the changes on the site over 9 months.

<div class="row">
  <div id="viewerBefore"></div>
  <div id="viewerAfter"></div>

  <style>
    #viewerBefore {
      width: 49%;
      height: 500px;
      float:left;
    }
    #viewerAfter {
      width: 49%;
      height: 500px;
      float:right;
    }
  </style>

  <script>
    var viewerBefore = new PhotoSphereViewer({
      container: 'viewerBefore',
      panorama: '{{ site.baseurl }}/img/DJI_0986.JPG',
      time_anim: 1500,
      default_long: -0.15,
      default_lat: -0.9,
      caption: 'October 2019.',
      navbar: false,
      mousewheel: false,
      anim_speed: '1rpm'
    });

    var viewerAfter = new PhotoSphereViewer({
      container: 'viewerAfter',
      panorama: '{{ site.baseurl }}/img/DJI_0402.JPG',
      time_anim: 1500,
      default_long: -0.15,
      default_lat: -0.92,
      caption: 'July 2020',
      navbar: false,
      mousewheel: false,
      anim_speed: '1rpm'
    });

  </script>
</div>
## Hyperlapse video
This is the first of two videos produced for Porirua Development. The second will be released in the near future.
<div class="row">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/ZAoD7ShRC7s?controls=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
