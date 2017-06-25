---
title: profile
keywords: user, profile, name, image
last_updated: June 24, 2017
summary: "A steem users profile information"
sidebar: opensteem_sidebar
permalink: profile
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
        <td>A image that represents that user.</td>
        <td><a href="/ImageObject">ImageObject</a></td>
      </tr>
      <tr>
        <td>first_name</td>
        <td>A string that represents the first name of the user.</td>
        <td>string</td>
      </tr>
      <tr>
        <td>last_name</td>
        <td>A string that represents the last name of the user.</td>
        <td>string</td>
      </tr>
      <tr>
        <td>full_name</td>
        <td>A string that represents the full name of the user.</td>
        <td>string</td>
      </tr>
      <tr>
        <td>about</td>
        <td>A description of the user.</td>
        <td>string</td>
      </tr>
      <tr>
        <td>location</td>
        <td>The location of the user.</td>
        <td>string</td>
      </tr>
    </tbody>
  </table>
</div>

## Example

    {
    	"profile": {
    		"image": {
    			"@type": "ImageObject",
    			"url": "https://www.example.com/image.jpeg",
    			"base64": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH4QYYFRgqSGzYQwAAAA1JREFUCNdjYGBg+A8AAQQBAKTgrDEAAAAASUVORK5CYII=",
    			"width": 50,
    			"height": 50
    		},
    		"full_name": "John Smith",
    		"about": "I am a generic user",
    		"location": "Earth"
    	}
    }

{% include links.html %}
