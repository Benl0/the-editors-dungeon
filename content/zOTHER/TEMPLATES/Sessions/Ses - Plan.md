---
title: 
sessionNum: <% tp.system.prompt("SessionNum","0") %>
sessionDate: 
publish: false
cssclasses: 
date: <%tp.file.creation_date()%>
type: session
tags:
  - <%tp.file.folder()%>/Session
  - <%tp.file.folder()%>/GM
world: <%tp.file.folder()%>
campaign: <%tp.file.folder()%>
location: 
description: 
summary:
---
##### Back:  || Session: 

# Session n.


---
# Encounters


---
# Minutes


<%tp.file.move("300 CAMPAIGNS/Garde/zGM/SESSIONS/"+tp.file.title)%>