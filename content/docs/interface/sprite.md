+++
title = "Sprite animation editor"
description = "Dahlia Studio sprite animation editor."
date = 2024-02-02T08:08:00+00:00
updated = 2024-02-02T08:08:00+00:00
draft = false
weight = 40
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "This is where you can create and edit animation sequences, which are referred to as <i>animation flipbooks</i> in dahlia."
toc = true
top = false
+++

{{ image(name="sprite-editor.jpg") }}

## Layout

The arrow on the top-left of the menu bar serves to save any changes you've made as well as return you to the main editor.

The name of the current animation flipbook is displayed on the right side of the 2 sidebar buttons.

## Animation flipbooks

These are simply containers that hold multiple animation sequences. When compiled, they produce a lua table that contains multiple sequences, similar to what is described [here](https://docs.coronalabs.com/api/library/display/newSprite.html#multiple-sequences).

## Selecting animation frames

You can select and deselect frames individually by clicking on them. You can also use the *select all* and *remove all* buttons in the frame order tab to do batch selection and deselection.

Frames will be added in their order of selection when selected manually. Batch selection adds frames in the order that they appear in their source imagesheet.

## Sequences

This sidebar is where you can create new animation sequences and select sequences to edit. When creating a new sequence, you'll need to give it a name, as well as choose one of the imagesheets you've already added to your project.

## Frame Order

This tab lists the animation frames you've selected as part of the final animation. You can re-order these frames by clicking their arrows to move them up or down.

## Animation

This tab is where you can preview and edit the animation that the active sequence will play. You can also move the animation a single frame at a time using the *previous* and *next* buttons.
