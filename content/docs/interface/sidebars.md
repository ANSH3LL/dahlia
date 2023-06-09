+++
title = "Editor sidebar tabs"
description = "Dahlia Studio editor sidebar tabs."
date = 2023-05-22T08:08:00+00:00
updated = 2023-05-30T08:08:00+00:00
draft = false
weight = 30
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "An in-depth explanation of the contents of the tabs found in the editor sidebars."
toc = true
top = false
+++

{{ image(name="sidebars.jpg") }}

## Toolbox

This tab contains all the objects and resources that you can create and use in your project.

## Artifacts

This tab contains all the resources you've created, grouped by type.

## Hierarchy

This tab contains all the objects in the current scene. Objects are organized in colored capsules that represent layers. Objects are ordered by `z-index`, with the top-most object being the last in the list. For example, in the image above, the image prop named "game_over" is on top of all the other objects in the foreground layer.

Any layer you create is represented twice; as an entry in its parent layer's capsule and as an independent capsule that can contain other objects.

To select and edit a layer's properties, as with any other object, click its entry in its parent layer's capsule. For example, in the image above, to edit the properties of the layer named "pipe1", you would click on its entry in the foreground layer's capsule.

Default layers (`Background`, `Foreground` and `Hotspot`) cannot be selected or edited. A capsule can be collapsed by clicking in its title section. The eye icons can be used to hide objects in the viewport. An object can be selected by clicking on its entry in its parent layer's capsule.

## Inspector

This tab is where you can edit the properties of selected objects. These properties may vary depending on the currently selected objects. Properties are organized in capsules that can be collapsed by clicking in their title sections.

When editing the contents of a textbox, such as an object's name, press `Enter` to submit the value you've entered and `Escape` to cancel editing. If the value you entered is invalid, the textbox will revert to its previous value. Otherwise, the value you entered will replace the previous one.
