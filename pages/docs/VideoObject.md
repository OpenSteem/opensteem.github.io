---
title: VideoObject
keywords: video, audiovisual, object
last_updated: June 24, 2017
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
        <td>duration</td>
        <td>The duration of the video recording in <a href="https://en.wikipedia.org/wiki/ISO_8601">ISO 8601</a> format.</td>
        <td>string</td>
        <td><code>P3M23S</code></td>
      </tr>
    </tbody>
  </table>
</div>

## Example

    {
        "@type":"VideoObject",
        "url":"https://www.example.com/video.mp4",
        "base64":"data:video/mp4;base64,iVBORw0KGgoAAAANS ... 8fH87+aPqxCcRN8TsB",
        "duration":"P3M14S"
    }

{% include links.html %}
