---
title: app
keywords: app, appname, client
last_updated: June 24, 2017
summary: "Identifies the application that created the post"
sidebar: opensteem_sidebar
permalink: app
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
        <td>name</td>
        <td>A string containing the lowercase name of the application.</td>
        <td>string</td>
        <td><code>appname</code></td>
      </tr>
      <tr>
        <td>version</td>
        <td>The version of the application that created a particular post.</td>
        <td>float</td>
        <td><code>1.0</code></td>
      </tr>
    </tbody>
  </table>
</div>

## Example

    {
      "app":{
          "name":"appname",
          "version":1.0
      }
    }

{% include links.html %}
