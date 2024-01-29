# Welcome to *GreenEdge* docs

## To update the documentation, please follow these steps

### Layouts
All posts have *layouts* specified in the header. The structure of the layouts can be found and edited in the **_layouts** directory.


### New post
All posts are found under the **_post** directory, and should be named [DATE]-[name-of-post].md. Post also need a header at the top E.g.:

```
---
layout: post
title:  "Edit Business unit information"
category: business-unit
permalink: /business-unit
---
```
All pages get rendered to html and can be found under the **_site** direcory

All *posts* should have a lab, which should get accessed through a button on the bottom of the page:

``` html
<a class="offset-5 btn btn-success btn-lg" href="/business-unit-lab" role="button">Go to lab</a>
``` 

### Images
Images should be saved in the **assets** directory and can be use as:

```
<img src="assets/images/edit-business-unit-lab.PNG">
```