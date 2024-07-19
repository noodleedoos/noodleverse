---
up: "[[Home]]"
tags:
  - area
archive:
---
## Related Sections
```dataview
list FROM #section and [[]]
```

## Related Courses
```dataview
list FROM #course and [[]] and !"100 - Meta"
sort file.name asc
```

## Related Units
```dataview
list FROM #unit and [[]] and !"100 - Meta"
sort file.name asc
```

## Related Lectures
```dataview
list FROM #lecture and [[]] and !"100 - Meta"
sort file.name asc
```

## Related Concepts
```dataview
list FROM #concept 
where contains(area, "[[]]")
```