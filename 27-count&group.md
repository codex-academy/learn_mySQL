---
layout: default
title: Counting and selecting grouped records
---

# Now its the time for grouping our fields but also counting at the very same time 

`SELECT *,(SELECT COUNT([column]) FROM [table]) AS count FROM [table] GROUP BY [column];`
