---
title: "Gallery of images"
excerpt: "Gallery"
sitemap: false
permalink: /test_img.html
redirect_from:

---


{% include base_path %}

{% comment %}

Include Image Gallery

{% include image-gallery-with-thumbs.html folder="files/test/1" items_per_line="3" %}

Include Image Gallery

{% include image-gallery-with-thumbs.html folder="files/test/2" %}

Include Video Gallery

{% include video-gallery.html folder="files/test/2" %}

Include One Video

{% include one-video.html file="files/test/3/1.mp4" width_percent="50"%}

{% endcomment %}


{% include video-preview-with-thumbs.html video_file="/files/test/2/00001.mp4" %}

<details>
  <summary>Those are in a folder</summary>

{% include video-preview-with-thumbs.html image_folder="files/test/2" items_per_line="6" %}

</details>

<details>
  <summary>Those are in another folder</summary>

{% include video-preview-with-thumbs.html image_folder="files/test/4" items_per_line="6" %}

</details>


