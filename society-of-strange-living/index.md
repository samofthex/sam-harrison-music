---
layout: video
show_meta: false
title: "The Society of Strange Living"
subheadline: "Introducing..."
teaser: "Music starting to sound the same to you? Relax, here's a band with a new take on just about everything. Strange by name and nature - not only is their drum kit made from a washing machine, these lovely guys are about the most rock 'n' roll people you'll meet, on or off stage. "
tags:
    - post format
categories:
    - design
iframe: "<iframe width='970' height='546' src='//www.youtube.com/embed/XR3S80yDGvY' frameborder='0' allowfullscreen></iframe>"
#
# These video settings are totally optional. It's only purpose
# is SEO, so that videos show up in Google hopefully with a 
# thumbnail.
# More › https://developers.google.com/webmasters/videosearch/schema?hl=en&rd=1
#
# embedURL – A URL pointing to a player for the specific video.
# contentURL – A URL pointing to the actual video media file
# thumbnailUrl – A URL pointing to the video thumbnail image file.
#
video:
    embedURL: "https://www.youtube.com/embed/XR3S80yDGvY"
    contentURL: "https://www.youtube.com/watch?v=XR3S80yDGvY"
    thumbnailUrl: "http://img.youtube.com/vi/XR3S80yDGvY/maxresdefault.jpg"
---
<!--more-->

## About the video...

> This video is a quick mash up of some of our shows so far. It's far from perfect, but we're a fairly new band and there's new things on the way! :-)</cite>

{% raw %}{% include gallery %}
image:
   thumb: "gallery-example-1-thumb.jpg"
gallery:
    - image_url: gallery-example-1.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-2.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-3.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-4.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-5.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-6.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-7.jpg
      caption: Great images by Unsplash.com
    - image_url: gallery-example-8.jpg
      caption: Great images by Unsplash.com
---
{% endraw %}
You just need to choose a template like the [`page`][3]- or [`page-fullwidth`][4]-template and then just use `{% raw %}{% include gallery %}{% endraw %}`.
<!--more-->

{% include gallery %}


## How to embed a gallery

`{% raw %}{% include gallery %}{% endraw %}` lets you easily embed a gallery into your post. To use the gallery-include...


### Step 1

1. Make two images: a thumbnail and a big image.
2. Name the thumbnail *gallery-image-thumb.jpg* and...
3. ...name the big *gallery-image.jpg*.
4. Place them in the *images*-folder.


### Step 2

Define the big version in frontmatter,  

~~~
gallery:
    - image_url: gallery-image.jpg
~~~

If you like captions, give each image a caption:

~~~
gallery:
    - image_url: gallery-image.jpg
       caption: Starting Page with huge One Logo
~~~

### Step 3

Add the include whereever you want in your content with `{% raw %}{% include gallery %}{% endraw %}`.

{% include alert info='Have a look at this example-entry. And have a look into the images-folder. :)' %}


Source: [The Society of Strange Living Top Secret HQ](https://www.youtube.com/watch?v=XR3S80yDGvY)
