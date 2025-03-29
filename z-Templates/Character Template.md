---
aliases: 
gender: 
age: 
vitality: Alive
profession: 
touch: None

associated-group: 

archetype:
desire:
fear:
strength:
weakness:

tags:
icon: FasUserLarge
---

<%* 
const currentPath = tp.file.folder(true);
const targetFolder = "Characters/"; 
const inTarget = currentPath.startsWith(targetFolder)
if (!inTarget) { 
	await tp.file.move(targetFolder + tp.file.title); 
}
_%>

> [!infobox]
> # `=this.file.name`
> %% Place Image on next line %%
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Gender | `=this.gender` |
> Age | `=this.age` |
> Condition | `=this.vitality` |
> Profession | `=this.profession` |
> Group | `=this.associated-group` |
> [[Touch]] | `=this.touch` |
> ###### Personality
> Type |  Stat |
> ---|---|
> Archetype | `=this.archetype` |
> Strength | `=this.strength` |
> Weakness | `=this.weakness` |
> Desire | `=this.desire` |
> Fear | `=this.fear` |
## Overview

## History

## Relationships

## Clues and Information
