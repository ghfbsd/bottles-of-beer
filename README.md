# bottles-of-beer

troff/groff program to write out verses of the song, "99 bottles of beer on the wall."

Use by saying,

```
groff -t -me -r y=N bottles > bottles.ps
```

where `N` (>0) is the number of verses you want (defaults to a short number, not
99).  View `bottles.ps` with your favorite PostScript viewer.
