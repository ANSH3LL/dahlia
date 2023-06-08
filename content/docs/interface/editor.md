+++
title = "Project editor"
description = "Dahlia Studio project editor screen."
date = 2023-05-22T08:08:00+00:00
updated = 2023-05-30T08:08:00+00:00
draft = false
weight = 20
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "This is where you'll spend the most time in dahlia. Here, you can create and edit the scenes/levels that make up your project."
toc = true
top = false
+++

Dahlia studio makes use of <a href="https://docs.coronalabs.com/api/library/composer" target="_blank">composer</a> by default to manage the scenes in your project. However, you can switch to a scene manager of your choice by editing your project's `scene scripts` if composer doesn't meet your project's needs. You could also edit the scene script template found at `Dahlia Studio/Resources/assets/stubs/scene.txt` for a more permanent effect.

## Editor components

<img src="/images/editor.png" width="100%"/>

<hr style="margin-top:30px;margin-bottom:25px;" />

**1. Toggle** `library` **sidebar** &mdash; Clicking this button will show the library sidebar if it was closed.

**2. Toggle** `content` **sidebar** &mdash; Clicking this button will show the content sidebar if it was closed.

**3. Finish line plot** &mdash; This button only works when drawing a line shape. Click it when you're done drawing to create a line object.

**4. Cancel drawing** &mdash; This button only works when drawing a line/polygon or placing an object on the scene. Click it to cancel drawing or object creation.

**5. Save current scene** &mdash; Clicking this button will save the current scene to disk.

**6. Export project** &mdash; Clicking this button will export the project. An exported project can be built or run in the simulator like any other solar2D project.

**7. Editor sidebar** &mdash; Sidebars contain tabs where you can interact with various contents of your project. There are 2 sidebars in the project editor, *library* and *content*.

**8. Scenes list** &mdash; This is where all scenes your project contains are shown. You can click on any entry in the list to view its corresponding scene. You can also delete a scene by clicking the &#10005; button.

**9. Scene viewport** &mdash; This is where your scene's contents are displayed. Objects in your game will appear as they do in the viewport.

**10. Content size bounding box** &mdash; This rectangle represents your project's content size and orientation.

**11. Center guides** &mdash; These lines represent the horizontal and vertical center points of your project when displayed on a screen.

**12. Cursor coordinates** &mdash; The position of your cursor relative the scene is displayed here.

**13. Zoom percentage** &mdash; The extent by which you have zoomed in/out is displayed here. You can also use the + and &ndash; buttons to zoom in or out.

## Viewport navigation
