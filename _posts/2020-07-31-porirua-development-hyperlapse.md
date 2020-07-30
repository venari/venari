---
author: Leigh
layout: post
---

This has been a fun project to work on with [Porirua Development][porirua-development] over the last 16 months, capturing the enormous progress that has taken place at Castor Crescent in Porirua, transforming it from a neglected field into 53 new homes.

Work undertaken:

* 8 site visits capturing video
* 30+ hours editing, and further refining the process


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
