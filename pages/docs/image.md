---
title: image
keywords: post, image, thumbnail
last_updated: June 24, 2017
summary: "A featured image for a particular post"
sidebar: opensteem_sidebar
permalink: image
folder: docs
---
## Properties

<div class="table-responsive">
  <table class="table">
    <thead>
      <tr>
        <th>Tag</th>
        <th>Description</th>
        <th>Type</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>image</td>
        <td>A single featured image for the post.</td>
        <td><a href="/ImageObject">ImageObject</a></td>
      </tr>
    </tbody>
  </table>
</div>

**NOTE:** `image` is designed for one image, for multiple, use [images](/images) instead

## Example

    {
      "image":{
          "@type":"ImageObject",
          "url":"https://www.example.com/image.jpeg",
          "base64":"data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH4QYYFRgqSGzYQwAAAA1JREFUCNdjYGBg+A8AAQQBAKTgrDEAAAAASUVORK5CYII=",
          "width":1280,
          "height":720
      }
    }

{% include links.html %}
