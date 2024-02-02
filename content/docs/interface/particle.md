+++
title = "Particle editor"
description = "Dahlia Studio particle editor."
date = 2024-02-02T08:08:00+00:00
updated = 2024-02-02T08:08:00+00:00
draft = false
weight = 50
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "This is where you can edit particle resources, which hold the configuration information used by particle emitters."
toc = true
top = false
+++

{{ image(name="particle-editor.jpg") }}

## Layout

The arrow on the top-left of the menu bar serves to save any changes you've made as well as return you to the main editor.

The name of the current particle resource is displayed on the right side of the sidebar button.

The sidebar contains panels that let you edit the configuration of the particle emitter. These panels each correspond to the 6 groups of properties that particle emitters have in solar2d.

For more information on particle emitter configuration, visit [this link](https://docs.coronalabs.com/api/type/EmitterObject/index.html#properties).

## Emitter panel

The duration field in this panel has a checkbox that allows you to set or unset *endless emission*.

When this checkbox is off, you can set the length of time (in milliseconds) that the emitter should emit particles before stopping. You can do this by typing in the duration textbox that will now be enabled.

You can also start or stop the emitter by clicking the small button next to the checkbox label. Do note that this button is only available to use when the emitter is set to emit particles for a fixed duration. Enabling endless emission disables this button.

To make use of emitter mapping in your exported project, you'll need to build it with solar2d version [2023.3692](https://github.com/coronalabs/corona/releases/tag/3692) and later.
