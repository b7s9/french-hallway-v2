---
title: "The LATCH Principle: How to Display a Lot of Information"
description: A theory on content organization for discovery, especially search results.
pubDate: Jan 18 2024
---
Displaying a lot of information in a content discovery use case (eg. Browse, Search, Feeds), is a tricky task. Often the most "powerful" feeling searches will offer a combination of the following filters/sorts. It is your responsibility as the designer to know the best default for your product, and to what degree the other filters may be necessary.

* L = Location
* A = Alphabetical
* T = Time. Recent/Old/Significant periods
* C = Category. Static Sibling relationships
* H = Hierarchy. Arbitrary gradients, such as price. aka non-alphabetical Sorting.

[Medium Article explaining the LATCH concept in greater detail](https://uxmovement.com/navigation/how-to-design-content-filters-for-better-user-browsing/)

## Location

Geographic Information tends to be most useful in products with a massive amount of data, eg. browsing new albums by city on Bandcamp

![Bandcamp new music feed filtered by city](/images/bandcamp-filter-location.jpg)

...or where the use case is specifically about physical movement or location, eg. Google maps

![Google's interactive map](/images/google-maps-filter-location.jpg)

## Category

This refers to a peer category system. In one system, there are "categories", which are typically between 2-12, defined by the system's designer, and only associate one category per post. For example, here is MetaFilter displaying their main 8 categories.

![MetaFilter categories](/images/metafilter-categories.png)

Another popular system is tags, which are typically allowed to be virtually infinite in number, defined by a user/content author, and may associate many tags per post.

![MetaFilter popular tags cloud](/images/metafilter-popular-tags.png)

## Hierarchy

Perhaps not the best named of the filters in LATCH, this filter refers to arbitrary gradients, such as cost of a product, height, width, quality, etc.

## Final Thoughts

Lastly, I wonder, does a representation of a file system count as location, category, or hierarchy? Especially in the age of products obscuring file/folder relationships (I'm not a huge fan of that trend), this seems like an odd case. I think the parent-child relationships are the primary key in the equation, because files can only live in one place, eg. a folder is a category. File systems do make good use of sorting by alpha, created/updated, other metadata available, and grouping by tags.

![Github File system](/images/github-file-system.png)

![Mega File System](/images/mega-file-system.png)

One other item of note is that sorting is a slightly different UX pattern from grouping. See Gestalt Psychology for further notes.