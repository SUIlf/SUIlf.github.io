---
layout: splash
permalink: /gallery/
title: "Photo gallery"
author_profile: false
gallery:
  - url: /assets/images/gallery/harsha_defense_1.png
    image_path: /assets/images/gallery/harsha_defense_1.png
    alt: "Congratulations Dr. Harsha Kokel on successful PhD defense!"
    title: "Congratulations Dr. Harsha Kokel on successful PhD defense!"
  - url: /assets/images/gallery/harsha_defense_2.png
    image_path: /assets/images/gallery/harsha_defense_2.png
    alt: "Harsha Kokel with her defense committee after her successful PhD defense."
    title: "Harsha Kokel with her defense committee after her successful PhD defense."
  - url: /assets/images/gallery/SN_bday_2022_7.png
    image_path: /assets/images/gallery/SN_bday_2022_7.png
    alt: "Celebrating Professor Natarajan's birthday!"
    title: "Celebrating Professor Natarajan's birthday!"
  - url: /assets/images/gallery/SN_bday_2022_6.png
    image_path: /assets/images/gallery/SN_bday_2022_6.png
    alt: "Celebrating Professor Natarajan's birthday!"
    title: "Celebrating Professor Natarajan's birthday!"
  - url: /assets/images/gallery/SN_bday_2022_4.png
    image_path: /assets/images/gallery/SN_bday_2022_4.png
    alt: "Birthday cake!"
    title: "Birthday cake!"
  - url: /assets/images/gallery/SN_bday_2022_3.png
    image_path: /assets/images/gallery/SN_bday_2022_3.png
    alt: "Celebrating Professor Natarajan's birthday!"
    title: "Celebrating Professor Natarajan's birthday!"
  - url: /assets/images/gallery/SN_bday_2022_1.png
    image_path: /assets/images/gallery/SN_bday_2022_1.png
    alt: "Celebrating Professor Natarajan's birthday!"
    title: "Celebrating Professor Natarajan's birthday!"
---

<link rel="stylesheet" href="/assets/css/bootstrap.css">

<style>
  img{
      max-width:345px;
      max-height:258px;
      OBJECT-FIT:contain;
  }
  .mfp-title {
    text-align:center;
    font-size:2em;
    line-height:35px
  }

  .entry-headers {
    padding-top: 1.0em;
  }

#gridid i {
    font-size: 16px;
    font-style: italic;
}

.page__footer-follow li {
  display: inline-block;
  padding-top: 5px;
  padding-bottom: 20px;
  font-size: .8em;
  text-transform: none;
}
</style>

<div style="padding-bottom: 20rem;" class="container-home page__other__hero--overlay">
<h1 style="text-transform: capitalize" class="entry-headers"> {{page.title}} </h1>

{% include gallery id="gallery" class="gallery-thumbnail"  %}

</div>

<div style="position: absolute; bottom: 0;" class="page__footer">
  <footer-new>
    <div class="row">
      <div id="gridid" class="col-sm-12">
        <div class="row">
          <div class="col-sm-6 clearfix" style="padding-left: 30px; padding-right: 30px">
            <div class="page__footer-follow">
              <ul class="social-icons">
                <li><strong>Access:</strong><br>Nihonbashi 1-chome Mitsui Building, 15th floor,<br>1-4-1 Nihonbashi,Chuo-ku, Tokyo<br>103-0027, Japan &nbsp; <a href="https://goo.gl/maps/KfJb19p3ZQLqYjae7" rel="nofollow noopener noreferrer">（<i style="font-style:normal" class="fa fa-location-arrow" aria-hidden="true"></i> Map） </a></li>
              </ul>
            </div>
          </div>
          <div class="col-sm-6 clearfix" style="padding-left: 30px; padding-right: 30px">
          <!-- start custom footer snippets -->
          <!-- end custom footer snippets -->
            <div class="page__footer-follow">
              <ul class="social-icons">
                <li><strong>Contact Info:</strong><br>Email: qibin.zhao [at] riken.jp &nbsp;*Please replace "[at]" with "@"<br>Tel: +81-(0)3-6225-2539<br><strong>Follow:</strong>&nbsp;<a href="https://github.com/" rel="nofollow noopener noreferrer"><i style="font-style:normal" class="fab fa-fw fa-github-square" aria-hidden="true"></i> GitHub</a>&nbsp;&nbsp;&nbsp;<a href="https://twitter.com/" rel="nofollow noopener noreferrer"><i style="font-style:normal" class="fab fa-fw fa-twitter-square" aria-hidden="true"></i> Twitter</a>&nbsp;&nbsp;&nbsp;<a href="https://www.youtube.com/" rel="nofollow noopener noreferrer"><i style="font-style:normal" class="fab fa-fw fa-youtube-square" aria-hidden="true"></i> YouTube</a></li>
              </ul>
            </div>
          </div>
          <div class="page__footer-copyright" style="padding-left: 30px; padding-right: 30px; color:#808080">© 2023 Tensor Learning Team. Powered by <a href="https://jekyllrb.com" rel="nofollow">Jekyll</a>.
          </div>
        </div>
      </div>
    </div>
