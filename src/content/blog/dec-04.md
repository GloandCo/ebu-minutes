---
title: 'HTML Subgroup'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Dec 04 2024'
---

### Action points
- Get questions together on current proposals
- Work on pros and cons for webcomponents

### Discussion

Spoke about our work from last week.

One of our members Davy walked through the repo to explain how they understood the repo allowing us to make sure it's understood properly and to answer any questions that come up.

Not sure on what status would be within the renderer. - We will look to add some definition but it's built to be a potential vendor hook for future extension.

The export graphic endpoint api, can be used to export the main intention is that's what's used to load resources

Confusion on the render target, it is intentionally vague as we don't want to impose how it works, but it is a layer based render. Each render target can be a target. However a renderer might work in different ways. Ie one area for lower thirds and one area for locators and they could be their own targets.

Render target could be web pages/iframes/areas etc - is target the correct word? 

A render target can run 0, 1 or more graphics.

Graphics instance - How does a graphic look like? Current proposal is webcomponent and manifest.json.

A small discussion about how we shouldn't be building the connection between server and renderer instead we should be discussing how it could be included especially with vendor specific renders.

We spoke about JSON schema, and how we can use a defined graphics schema to help build manifest files for specific graphics.

We spoke about how we can support multiple languages inside the values. This is based on W3C language maps. There will be a proposal written up to talk about ongoing concerns. 

We spoke about if webcomponents were right for the market. We feel most people would struggle to understand the use of webcomponents as it's not something that is used by most developers even if it's a web standard. We need to make a list of pros and cons to work out if it's the right route to go down.