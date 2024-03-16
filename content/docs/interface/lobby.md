+++
title = "Start-up screen"
description = "Dahlia Studio start-up screen."
date = 2023-05-22T08:08:00+00:00
updated = 2023-05-30T08:08:00+00:00
draft = false
weight = 10
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "This is the first screen you will encounter in dahlia. Here, you can create new projects as well as open existing ones. A list of your 20 most recently opened projects is also displayed when available."
toc = true
top = false
+++

{{ image(name="lobby.jpg") }}

### Creating a new project

When creating a new project, you will be presented with a dialog that allows you to perform basic project configuration. The values you set here determine how your game will be displayed on players' devices.

**Important**
<blockquote>
In dahlia studio, content width and height values should be set to match the selected project orientation.
<br><br>
Therefore, the following should be kept in mind:
<br>
- A project with <b>portrait</b> orientation should have a width that is smaller than its height, such as <code>360x640</code>.
<br>
- A project with <b>landscape</b> orientation should have a width that is larger than its height, such as <code>640x360</code>.
</blockquote>

{{ image(name="new-project.jpg") }}

### Content scaling

There are 3 values to choose from:

1. **letterbox** &mdash; scales the content area to fill the screen while preserving the same aspect ratio. The entire content area will reside on the screen, but this might result in black bars on devices with aspect ratios that differ from your content size aspect ratio.
2. **zoomEven** &mdash; scales the content area to fill the screen while preserving the same aspect ratio. Some content may bleed off the screen edges on devices with aspect ratios that differ from your content size aspect ratio.
3. **zoomStretch** &mdash; scales the content area to fill the entire screen on any device, ignoring the content size aspect ratio.

More information on how content scaling works can be found <a href="https://docs.coronalabs.com/guide/basics/configSettings/index.html#scale" target="_blank">here</a>.
