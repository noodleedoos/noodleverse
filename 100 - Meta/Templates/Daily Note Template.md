---
tags:
  - dailyNote
up:
  - "[[Quest Log]]"
week:
---
## Today's Main Quest
## Quest Log
[Summary:: ]
[Grateful:: ]
[Memory:: ]
[Life-learning:: ]

[Symptoms:: ]
[Medication:: ]
[Emotions:: ]
## Letter Stew

## Activity Log
### Projects worked on:
```dataview
table 
FROM #project and [[]]
```

### Modified Notes:
```dataview
TABLE file.tags as "Note Type", file.cday
from "" and !#project
WHERE contains(dateformat(file.mday, "yyyy-MM-dd HH:mm"), this.file.name) 
SORT file.name
```

### Created Notes:
```dataview
TABLE file.tags as "Note Type", file.cday
from ""
WHERE contains(dateformat(file.cday, "yyyy-MM-dd HH:mm"), this.file.name)
SORT file.name
```