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
        <td>A small image that represents that user.</td>
        <td><a href="/ImageObject">ImageObject</a></td>
      </tr>
      <tr>
        <td>banner</td>
        <td>A large image that represents that user.</td>
        <td><a href="/ImageObject">ImageObject</a></td>
      </tr>
      <tr>
        <td>name</td>
        <td>A dictonary containing the <code>user</code>, <code>full</code>, <code>first</code>, and <code>last</code> keys.</td>
        <td>dict</td>
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
    		"banner": {
    			"@type": "ImageObject",
    			"url": "https://www.example.com/image_large.jpeg",
    			"base64": "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAYAAAAfFcSJAAAABmJLR0QA/wD/AP+gvaeTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAB3RJTUUH4QYYFRgqSGzYQwAAAA1JREFUCNdjYGBg+A8AAQQBAKTgrDEAAAAASUVORK5CYII=",
    			"width": 1280,
    			"height": 720
    		},
    		"name": {
    			"user": "johnsmith",
    			"full": "John Smith",
    			"first": "John",
    			"last": "Smith"
    		},
    		"about": "I am a generic user",
    		"location": "Earth"
    	}
    }

{% include links.html %}
