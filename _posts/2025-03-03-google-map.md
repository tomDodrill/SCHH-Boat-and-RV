---
layout: post
title: Post with a Google Map
description: Example post using an Iframe to embed a Google Map.
date: 2025-03-05
author: John Doe
tags: iframe
omit_header: false
---

### How to Embed a Google Map in a Post

- **Get the embed code from the Google Maps site**
    1. Go to **[Google Maps](https://www.google.com/maps)** and search for the location you want to embed.  
    1. Click the **"Share"** button (found on the left side or in the menu).  
    1. In the pop-up window, click on the **"Embed a map"** tab.  
    1. You will see a **preview of the map** inside a small box.  
    1. Below the preview, you’ll see an **HTML iframe code** (it starts with `<iframe src="https://...">`).  
    1. Click the **"Copy HTML"** button.  
- **Customize the map size** (Optional)
    In the `iframe tag`:
    - Change the value of the `width` attribute to `100%`
    - Delete the `height` attribute and value

### Example map

```markdown
<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d34306.774111100116!2d-80.75458230273426!3d32.19746255434643!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sus!4v1741636880949!5m2!1sen!2sus" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
```
Markdown - before size adjustment
`.caption`

<br/>

```markdown
<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d34306.774111100116!2d-80.75458230273426!3d32.19746255434643!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sus!4v1741636880949!5m2!1sen!2sus" width="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
```
Markdown - after size adjustment
`.caption`

<br/>

<iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d34306.774111100116!2d-80.75458230273426!3d32.19746255434643!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2sus!4v1741636880949!5m2!1sen!2sus" width="100%" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

Rendered map
`.caption`
