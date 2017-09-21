---
title: VideoObject
keywords: video, audiovisual, object
last_updated: September 16, 2017
summary: "A way to embed video directly onto the steem blockchain"
sidebar: opensteem_sidebar
permalink: VideoObject
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
        <td>A url pointing to an video file on the web.</td>
        <td>string</td>
        <td><code>https://example.com/video.mp4</code></td>
      </tr>
      <tr>
        <td>base64</td>
        <td>A base64 encoded video file that can be stored on the blockchain. Its recommended to only use this on short videos at low resolutions.</td>
        <td>string</td>
        <td><code>data:video/mp4;base64,iVBORw0KGgoAAAANS...</code></td>
      </tr>
      <tr>
        <td>ipfs_hash</td>
        <td>The IPFS hash of the item if stored using the Interplanetary File System</td>
        <td>string</td>
        <td><code>QmQY8FCpmfCPpYHTooxfBNYh88Y...</code></td>
      </tr>
      <tr>
        <td>duration</td>
        <td>The duration of the video recording in <a href="https://en.wikipedia.org/wiki/ISO_8601">ISO 8601</a> format.</td>
        <td>string</td>
        <td><code>P3M23S</code></td>
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
      <tr>
        <td>fps</td>
        <td>The number of frames per second of the video</td>
        <td>float</td>
        <td><code>30.0</code></td>
      </tr>
      <tr>
        <td>thumbnail</td>
        <td>A thumbnail taken from the video or other image that represents the video</td>
        <td><a href="/ImageObject">ImageObject</a></td>
        <td>See ImageObject</td>
      </tr>
    </tbody>
  </table>
</div>

## Example

    {
        "@type":"VideoObject",
        "url":"https://www.example.com/video.mp4",
        "base64":"data:video/mp4;base64,iVBORw0KGgoAAAANS ... 8fH87+aPqxCcRN8TsB",
        "ipfs_hash":"QmQY8FCpmfCPpYHTooxfBNYh88YdfbDUwAwjHH3Eze9vjv",
        "duration":"P3M14S",
        "width":1280,
        "height":720,
        "fps":30.0,
        "thumbnail":{
            "@type":"ImageObject",
            "url":"https://www.example.com/image.jpeg",
            "base64":"data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH4QYYFRgqSGzYQwAAAA1JREFUCNdjYGBg+A8AAQQBAKTgrDEAAAAASUVORK5CYII=",
            "ipfs_hash":"QmQY8FCpmfCPpYHTooxfBNYh88YdfbDUwAwjHH3Eze9vjv"
            "width":1280,
            "height":720
        }
    }

{% include links.html %}
