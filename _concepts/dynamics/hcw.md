---
layout: page
title: "Hill-Clohessy-Wiltshire Equations"
topic: "dynamics"
subtopic: "relative dynamics"
---

The intention of this space is to create an easily accessible compendium of useful tips and tricks that I've found throughout the ages while surfing the wonders of the WWW. 

## Command Line Tools

### Removing Lines From Text Files
Credit: [SiegeX](https://stackoverflow.com/questions/5410757/delete-lines-in-a-text-file-that-contain-a-specific-string)

For deleting text lines containing a particular string, I use `sed`, e.g.:

```bash
sed -i '/pattern/d' ./nameOfFile
```

### Reformatting Images