# Как проверял базу (`timchenko_food`)

Все проверки гонял от имени `inspector`[cite: 11, 12]:

```sql
SET ROLE inspector;
SET search_path TO timchenko_food, exts;