---
title: AudioObject
keywords: audio, music, sound, object
last_updated: June 24, 2017
summary: "A way to embed audio directly onto the steem blockchain"
sidebar: opensteem_sidebar
permalink: AudioObject
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
        <td>A url pointing to an audio file on the web.</td>
        <td>string</td>
        <td><code>https://example.com/audio.mp3</code></td>
      </tr>
      <tr>
        <td>base64</td>
        <td>A base64 encoded audio file that can be stored on the blockchain.</td>
        <td>string</td>
        <td><code>data:audio/ogg;base64,T2dnUwAC...</code></td>
      </tr>
      <tr>
        <td>duration</td>
        <td>The duration of the audio recording in <a href="https://en.wikipedia.org/wiki/ISO_8601">ISO 8601</a> format.</td>
        <td>string</td>
        <td><code>P3M23S</code></td>
      </tr>
    </tbody>
  </table>
</div>

## Example

    {
        "@type":"AudioObject",
        "url":"https://www.example.com/audio.ogg",
        "base64":"data:audio/ogg;base64,T2dnUwACAAAAAAAAAAA7/PA+AA ... 8fH87+aPqxCcRN8TsB",
        "duration":"P3M14S"
    }

{% include links.html %}
