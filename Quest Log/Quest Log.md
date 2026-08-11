# 📜 Quest Log

## Active Quests

```dataview
TABLE campaign AS "Campaign", tier AS "Tier", xp AS "XP", estimated AS "Time"
FROM "Quest Log"
WHERE status = "In Progress"
SORT created DESC
```

## Completed Quests

```dataview
TABLE campaign AS "Campaign", tier AS "Tier", xp AS "XP", completed AS "Completed"
FROM "Quest Log"
WHERE status = "Completed"
SORT completed DESC
LIMIT 30
```
