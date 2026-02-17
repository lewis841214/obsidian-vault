---
date: {{date:YYYY-MM-DD}}
day: {{date:dddd}}
week: {{date:ww}}
tags: [daily-note]
---

# {{date:YYYY-MM-DD}} {{date:dddd}}

## 🌅 Morning Thoughts


## 📋 Today's Priorities
- [ ] 
- [ ] 
- [ ] 

## 📝 Notes & Ideas


## 📚 What I Learned Today


## 🏆 Wins of the Day


## 🔗 Related Notes


## 📊 Daily Stats
```dataview
TABLE WITHOUT ID
  file.link as "Note",
  file.mtime as "Modified"
FROM "" 
WHERE file.mtime >= date({{date:YYYY-MM-DD}}) AND file.mtime < date({{date:YYYY-MM-DD}}) + dur(1 day)
SORT file.mtime DESC
LIMIT 10
```

---
*Created at {{date:HH:mm}}*
