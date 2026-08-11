---
type: campaign
purpose: 
active_quests: 0
xp: 0
---

# Campaign

## Purpose


## Active Quests

```dataview
TABLE tier AS "Tier", xp AS "XP", estimated AS "Time", status AS "Status"
FROM "Quest Log"
WHERE campaign = this.file.name AND status != "Completed"
SORT tier ASC
```

## Completed Quests

```dataview
TABLE xp AS "XP", completed AS "Completed"
FROM "Quest Log"
WHERE campaign = this.file.name AND status = "Completed"
SORT completed DESC
```

## Next Possible Quests

- 
