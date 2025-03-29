---
aliases: 
type:
status:

desire:
fear:

icon: FasUserGroup
---

<%* 
const currentPath = tp.file.folder(true);
const targetFolder = "Groups/"; 
const inTarget = currentPath.startsWith(targetFolder)
if (!inTarget) { 
	await tp.file.move(targetFolder + tp.file.title); 
}
_%>

> [!infobox]
> # `=this.file.name`
> `=this.aliases`
> %% Place Image on next line %%
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Status | `=this.status` |
> Agenda | `=this.desire` |
> ## Members
>```dataview TABLE  WHERE contains(associated-group, [[]]) 
>```
## Overview

## History

## Members

## Internal Politics

## External Politics

## Clues and Information
