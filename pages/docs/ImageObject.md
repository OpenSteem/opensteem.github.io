---
title: ImageObject
keywords: image, object
last_updated: September 16, 2017
summary: "A way to embed images directly onto the steem blockchain"
sidebar: opensteem_sidebar
permalink: ImageObject
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
        <th>Example</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>url</td>
        <td>A url pointing to an image on the web.</td>
        <td>string</td>
        <td><code>https://example.com/image.jpg</code></td>
      </tr>
      <tr>
        <td>base64</td>
        <td>A base64 encoded image that can be stored on the blockchain.</td>
        <td>string</td>
        <td><code>data:image/png;base64,iVBORw0KG...</code></td>
      </tr>
      <tr>
        <td>ipfs_hash</td>
        <td>The IPFS hash of the item if stored using the Interplanetary File System</td>
        <td>string</td>
        <td><code>QmQY8FCpmfCPpYHTooxfBNYh88Y...</code></td>
      </tr>
      <tr>
        <td>width</td>
        <td>The width of the image in pixels</td>
        <td>int</td>
        <td><code>1280</code></td>
      </tr>
      <tr>
        <td>height</td>
        <td>The height of the image in pixels</td>
        <td>int</td>
        <td><code>720</code></td>
      </tr>
    </tbody>
  </table>
</div>

## Example

    {
        "@type":"ImageObject",
        "url":"https://www.example.com/image.jpeg",
        "base64":"data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH4QYYFRgqSGzYQwAAAA1JREFUCNdjYGBg+A8AAQQBAKTgrDEAAAAASUVORK5CYII=",
        "ipfs_hash":"QmQY8FCpmfCPpYHTooxfBNYh88YdfbDUwAwjHH3Eze9vjv",
        "width":1280,
        "height":720
    }

{% include links.html %}
