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

> [!quote] *Session quote*

# Session n.
*short blurb*

## Character met:
- *wiki links*

> [!summary] Foundry Chat log
> *wiki link*

# location 1


# Location 2

<%tp.file.move("300 CAMPAIGNS/Garde/SESSIONS/"+tp.file.title)%>