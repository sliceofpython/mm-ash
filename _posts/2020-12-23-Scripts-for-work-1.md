---
title: "Post: Scripts For Work"
last_modified_at: 2020-10-09T16:20:02-05:00
categories:
  - Blog
tags:
  - PowerShell
  - readability
  - standard
---


## makes a word cloud from copied text
```Get-Clipboard | New-WordCloud -Path .\wordcloud.svg -Typeface georgia -ImageSize 720p -AllowRotation none```

## Advanced search with PowerShell
source: [devblogs.microsoft.com](https://devblogs.microsoft.com/scripting/use-windows-powershell-to-search-for-files/)

Get-Childitem –Path C:\ -Recurse
Get-Childitem –Path C:\ -Include *HSG* -Exclude *.JPG,*.MP3,*.TMP -File -Recurse -ErrorAction SilentlyContinue

$FindDate=Get-Date -Year 2020 -Month 11 -Day 10 
Get-ChildItem -Path C:\users\ -Include *txt -File -Recurse | Where-Object { $_.LastWriteTime -ge $FindDate }