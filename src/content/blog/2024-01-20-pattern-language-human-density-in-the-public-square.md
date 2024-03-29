---
title: "Pattern 123: Pedestrian Density"
description: How to measure the liveliness of a pedestrian plaza, and its
  application to social media apps.
pubDate: Jan 11 2024
---
### From the Book

> Many of our modern public squares, though intended as lively plazas, are in fact deserted and dead.

Liveliness of a public area is measured in square feet per square person. The proposed target is 150/sfpp, (range 100-300 ish) so the area feels alive. If the area is more than 1000/sfpp, then the public place may feel dead. The authors note that time plays an important factor here—a plaza may be expected to be dead in the morning and alive at night.

Depending on the scenario, the architect may want a more lively or dead space. But this pattern is assuming a public park or similar. Indoor spaces like music venues would be preferred to be more dense and more alive.

### Applied to Software Design

The most apparent example that springs to mind is the design density of a social media feed, for instance Mastodon or micro.blog. We could measure density in a few ways:

1. posts per hour (concept)
2. posts per viewport height (literal)

Perhaps the combination of the two is what gives a social media app the feeling of aliveness. I would consider feelings of reality/authenticity to be related to this pattern, but distinct, as it is most definitely possible for a social forum to be alive and full of garbage.
