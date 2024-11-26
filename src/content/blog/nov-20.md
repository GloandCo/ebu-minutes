---
title: 'Group Meeting'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Nov 20 2024'
---

### Action points
- Decide how graphics should be built for future proofing

### Discussion

Johan walked through the work they've been doing.

As a group we discussed why we'd be looking to use web components. We discussed that it would be the most suitable given it's current web standardisation and how it's a similar structure used in most frameworks so would be easily compatible.

We discussed the potential issues around poorly coded components or heavy usage components and agreed we could leverage iframes to consolidate the components and let the browser handle them better.

We discussed updating graphics and how we'll need to make sure graphics that are currently on air aren't deleted. This would be achieved with multiple delete options for first marking as deprecated then to actually be deleted.

We spoke about rendering logic and whether the template or the renderer should handle transition logic.

When using realtime graphics there will be the need to send out a batch command to hide all graphics or being playing multiple graphics.

Websockets within the renderer will need to be bidirectional to send and receive commands that alter the UI
