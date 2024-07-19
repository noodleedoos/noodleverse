---
up: "[[Home]]"
tags:
  - area
archive: 
limit: 100
mapWithTag: false
icon: dog
tagNames: 
filesPaths: 
bookmarksGroups: 
excludes: 
extends: all
savedViews: []
favoriteView: 
fieldsOrder:
  - 5JSjl1
  - 25sg0J
  - 22KbzS
  - eEEBtj
  - Cl1ldP
version: "2.8"
fields:
  - name: lecture
    type: MultiFile
    options: {}
    path: ""
    id: Cl1ldP
  - name: unit
    type: MultiFile
    options: {}
    path: ""
    id: eEEBtj
  - name: course
    type: MultiFile
    options: {}
    path: ""
    id: 22KbzS
  - name: section
    type: MultiFile
    options: {}
    path: ""
    id: 25sg0J
  - name: area
    type: MultiFile
    options: {}
    path: ""
    id: 5JSjl1
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