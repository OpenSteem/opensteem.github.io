---
title: images
keywords: post, images
last_updated: June 24, 2017
summary: "A list of ImageObjects"
sidebar: opensteem_sidebar
permalink: images
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
        <td>images</td>
        <td>A list of <a href="/ImageObject">ImageObject</a>'s for a single post.</td>
        <td>list</td>
      </tr>
    </tbody>
  </table>
</div>

**NOTE:** `images` is designed for many images, for one, use [image](/image) instead

## Example

    {
      "images":[
        {
            "@type":"ImageObject",
            "url":"https://www.example.com/image.jpeg",
            "base64":"data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH4QYYFRgqSGzYQwAAAA1JREFUCNdjYGBg+A8AAQQBAKTgrDEAAAAASUVORK5CYII=",
            "width":1280,
            "height":720
        },
        {
            "@type":"ImageObject",
            "url":"https://www.example.com/image.jpeg",
            "base64":"data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH4QYYFRgqSGzYQwAAAA1JREFUCNdjYGBg+A8AAQQBAKTgrDEAAAAASUVORK5CYII=",
            "width":1280,
            "height":720
        }
      ]
    }

{% include links.html %}
