# 📖 Daily Logs

```dataview
TABLE date AS "Date", quest AS "Quest", xp AS "XP", next_quest AS "Next Quest"
FROM "Daily Logs"
WHERE file.name != "Daily Logs"
SORT date DESC
LIMIT 30
```
