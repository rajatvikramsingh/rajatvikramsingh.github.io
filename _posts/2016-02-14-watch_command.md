---
layout: post
title: Watch the filesize of a file you're downloading in terminal
---
Recently I needed to watch the size of a file I was downloading and see how the size was increasing. I came across the command watch on unix. 
According to manpage of watch:
```
watch - execute a program periodically, showing output fullscreen
```
Sample Usage:
```
watch -n 5 "du -h <file name>"
```
Sample Output: (fullscreen)
```
Every 5.0s: du -h ./<file name>                                                         Wed Feb 15 20:36:48 2017

2.5G    ./<file name>
```
