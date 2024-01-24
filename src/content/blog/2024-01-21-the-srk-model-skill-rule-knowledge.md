---
title: "The SRK Model: Skill, Rule, Knowledge"
description: A framework to understand and prevent use error in system designs
pubDate: Jan 21 2024
---
The SRK (Skill, Rule, Knowledge) Framework was proposed by Jens Rasmussen in the 1980's as a branch of *Ecological Interface Design*. It is particularly useful for alarm and triage systems design ([3 mile island](https://en.wikipedia.org/wiki/Three_Mile_Island_accident) is common case study when learning this framework in a Human Factors Engineering class), but is a valuable consideration in any system design.

SRK can be used to identify at which stage in the human response process a use error occurs. 

1. Skill = low level subconscious/motor/anthropometry.
2. Rule = mid-level pattern recognition.
3. Knowledge = high-level Social/Environmental/Emotional factors.

A common set of use errors might be:

1. Skill: Hitting the wrong button because they are too small and too close together
2. Rule: Flipping the wrong switch because its function is not labeled clearly
3. Knowledge: Not informing relevant authorities about an issue because the operator is afraid they will lose their job

## Examples

### Skill

The easiest place to find skill use error on the web is in tiny mobile nav buttons that take a few tries to click, or are too far out of reach on giant modern phones.

![](/images/buddy-ios-14.png)

For instance, consider the cog menu button at the top right which would be laughably out of reach for right handed users on any device larger than an iphone 5. Hopefully it doesn't serve a critical function such that a user would regularly want to click on it.

### Rule

The following example from Cake Equity is a pattern that I like in physical products like hardware synthesizers, but doesn't feel intuitive in a digital UI setting. The pattern that I and most users are accustomed to is that a switch on a website represents a single idea as being on or off. The "Simulate conversion" switch tries to represent two mutually exclusive ideas, but the visual representation communicates on or off. 

![Cake Equity Two way labeled Switches](/images/cake-equity-web-285.png)

In contrast, I think Mixpanel handles this better with its segmented controllers

![Mixpanel segmented controller](/images/screen-shot-2024-01-23-at-21.40.52.png)

## Visibility of the Designer's Labor

Design for Skill use error, eg. the size, color, or distance between buttons is the most visible aspect of a designer's job, and rarely challenges business rules or social structures. GDPR laws about button presentation in cookies banners being a notable exception to the latter. If you know a designer, this type of work is likely what you perceive them doing.

A designer's work to create designs for Rule or Knowledge use error is less visible in the user interface. These require more research and stakeholder discussions. Outputs of the designer's labor here is mostly in system design documents not consumed by anyone other than key stakeholders and engineers. 

It is typical in online forum discussions, to see people intuitively distinguish UI Designers (making shiny buttons) from UX Designers (making systems), perhaps with a tone of defensiveness on the part of UX Designers.