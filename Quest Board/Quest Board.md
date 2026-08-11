# ⚔ Quest Board

> Contracts posted by the guild. Choose one. Begin.

## 🟢 Tiny Quests · 5–15 min

```dataview
TABLE campaign AS "Campaign", xp AS "XP", status AS "Status", estimated AS "Time", created AS "Created"
FROM "Quest Log"
WHERE status = "Available" AND tier = "Tiny"
SORT created DESC
```

## 🔵 Common Quests · 20–40 min

```dataview
TABLE campaign AS "Campaign", xp AS "XP", status AS "Status", estimated AS "Time", created AS "Created"
FROM "Quest Log"
WHERE status = "Available" AND tier = "Common"
SORT created DESC
```

## 🟣 Rare Quests · 45–90 min

```dataview
TABLE campaign AS "Campaign", xp AS "XP", status AS "Status", estimated AS "Time", created AS "Created"
FROM "Quest Log"
WHERE status = "Available" AND tier = "Rare"
SORT created DESC
```

## 🟠 Epic Quests · Multi-session

```dataview
TABLE campaign AS "Campaign", xp AS "XP", status AS "Status", estimated AS "Time", created AS "Created"
FROM "Quest Log"
WHERE status = "Available" AND tier = "Epic"
SORT created DESC
```

---

## 🎲 If You Cannot Decide

Pick the first quest whose time fits the time you have.

**The board decides. You adventure.**
