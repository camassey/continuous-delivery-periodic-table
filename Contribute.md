# Contribute to the Elements
Hello continuous deliverers! This is a usefully short guide on how to contribute to this list / visualisation of the elements of Continuous Delivery.


## Contributor license agreement
By submitting code you agree to the [LICENSE](/license.md) of this repository.

##The goal is to create a sensible Periodic Table of Continuous Delivery, not an endless list of terms and concepts.
This list can't be infinite! We still want it to build a sensible-looking periodic table, with groups, symbols and further reading. To that end, look for terms which can be pruned as well as what's missing.

## Everyone is welcome to suggest new / alternative elements (and associated further reading) or groups to the list.
It's true - you're all welcome to suggest better elements and references to the list. And by free, we mean free, really free.

## Steps to add or update an element

1. Pick the term you think should be pruned, altered or added, and match it to a category.
2. Decide how "heavy" the term is (i.e. the more opaque a term / the more you need to know about CD to understand it, the "heavier" it is), relative to the other elements in that category
3. Place the element in the list (ordered according to "weight", and list 
	1. The elemental symbol
	2. The element name 
	3. A short (~1 para) explanation of the term 
	4. A link to further reading.

### Guidelines

1. Unlike some projects, we prefer multiple small commits rather than one large change in a pull request - it's fine to have one pull request, but please make sure your title reflects what you've changed.
2. Use our standard for formatting the .md file. Check it out: [Formatting](#formatting)
3. Please try to order terms according to jargon "weight" *within each category* (i.e. the more opaque a term / the more you need to know about CD to understand it, the "heavier" it is).


### Formatting
+ All lists are ```.md``` files using GitHub-flavoured markdown!
+ The lists of [elements](/elements.md) have a little bit of structure to it. It's currently a bit of a brain-dump, so it'll need a bit of reordering. In the meantime, if you can suggest a better way to structure it, update the [TODO](/TODO.md) with the idea and / or raise an issue :)

Example from [Rollback and recovery](/Elements/Rollback-andRecover.md):
```
[...]
##Ms - Migrations scripts
A migration script alters a database from one state to another, 'migrating' the database between versions. This alteration can be as simple as adding or removing a column to a table, or a complex refactoring task such as splitting tables or changing column properties in a way that could affect the data it stores.

[https://www.simple-talk.com/sql/database-administration/using-migration-scripts-in-database-deployments/]

##Symbol - Element name
some copy to describe the element
[link to a post for further reading]

```

And that's it! 
