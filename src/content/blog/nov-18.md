---
title: 'Call between Johan & Ben'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Nov 18 2024'
---

### Action points
- Ben will be looking into what graphics could be built as example points
- Johan will be looking to move the renderer into the directory structure and continue with the reference server
- We'll need someone to try and build using the reference material to make sure it's fit for use

### Discussion

We discussed the work we'd done in the previous tools where Ben build on top of the component used for IBC to display a simple name card.

Johan talked through the changes he'd made to have a working renderer and the types he'd built for the structure around this.

We spoke about the reference and the definitions, they should be written out agnostically in plain text using pseudo code. The specs would be based on the JSON RPC specs because they're built very well.

Johans current work is ble to list graphics, get graphics and get graphic resources.

We spoke about the current GDD (graphics data definition) and how much we'd be using from that project and want to avoid copy and pasting it when people are currently using it, however there might be issues as it's owned and managed by Superfly.

The definitions are being build to be extended on in the future, vendors will be able to add vendor specific functions if they're prefixed correctly, allowing this project to expand in the future.

We discussed some of the difficulties with creating the HTML standard when it comes to render logic such as things overlapping or graphics altering themselves based on new elements coming in. We want to avoid telling people how they need to build things so we're unsure at this stage how to approach this.
