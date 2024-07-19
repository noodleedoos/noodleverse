---
up: "[[Home]]"
tags:
  - area
archive: 
fields:
  - name: emotions
    type: Multi
    options:
      valuesList:
        "1": happy
        "2": sad
        "3": angry
        "4": depressed
        "5": anxious
        "6": lost
        "7": afraid
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: dFaqrL
  - name: interoception
    type: Multi
    options:
      valuesList:
        "1": nauseous
        "2": healthy
        "3": headache
        "4": eyeache
        "5": tummyache
        "6": no-hunger
        "7": hungry
        "8": full
      sourceType: ValuesList
      valuesListNotePath: ""
      valuesFromDVQuery: ""
    path: ""
    id: UhfZBz
  - name: energy
    type: Number
    options:
      max: 10
      min: 0
    style:
      bold: false
    path: ""
    id: JN9AuJ
  - name: mood
    type: Number
    options:
      max: 10
      min: 0
    path: ""
    id: VsC0Ez
  - name: productivity
    type: Number
    options:
      max: 10
      min: 0
    path: ""
    id: mIIMaB
  - name: motivation
    type: Number
    options:
      max: 10
      min: 0
    path: ""
    id: WC38bb
  - name: nutrition
    type: Number
    options:
      max: 10
    path: ""
    id: IdJ8Jp
  - name: medication
    type: Boolean
    options: {}
    path: ""
    id: CSNcV2
  - name: triggers
    type: Input
    options: {}
    path: ""
    id: 6wjqeX
version: "2.15"
limit: 100
mapWithTag: true
icon: rat
tagNames: 
filesPaths: 
bookmarksGroups: 
excludes: 
extends: 
savedViews: []
favoriteView: 
fieldsOrder:
  - 6wjqeX
  - CSNcV2
  - IdJ8Jp
  - WC38bb
  - mIIMaB
  - VsC0Ez
  - JN9AuJ
  - UhfZBz
  - dFaqrL
---
## Related Sections
```dataview
list FROM #section   
where contains(area, "[[]]")
```

## Related Courses
```dataview
list FROM #course 
where contains(area, "[[]]")
```

## Related Units
```dataview
list FROM #unit  
where contains(area, "[[]]")
```

## Related Lectures
```dataview
list FROM #lecture  
where contains(area, "[[]]")
```

## Related Concepts
```dataview
list FROM #concept 
where contains(area, "[[]]")
```