```
 hey http://localhost:10000

Summary:
  Total:	0.0108 secs
  Slowest:	0.0080 secs
  Fastest:	0.0002 secs
  Average:	0.0022 secs
  Requests/sec:	18542.1581
  
  Total data:	9360 bytes
  Size/request:	46 bytes

Response time histogram:
  0.000 [1]	  |■
  0.001 [50]  |■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
  0.002 [43]  |■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
  0.003 [38]  |■■■■■■■■■■■■■■■■■■■■■■■■■■■■■■
  0.003 [34]  |■■■■■■■■■■■■■■■■■■■■■■■■■■■
  0.004 [16]  |■■■■■■■■■■■■■
  0.005 [12]  |■■■■■■■■■■
  0.006 [4]	  |■■■
  0.006 [0]	  |
  0.007 [0]	  |
  0.008 [2]	  |■■


Latency distribution:
  10% in 0.0007 secs
  25% in 0.0010 secs
  50% in 0.0020 secs
  75% in 0.0029 secs
  90% in 0.0041 secs
  95% in 0.0047 secs
  99% in 0.0073 secs

Details (average, fastest, slowest):
  DNS+dialup:	0.0002 secs, 0.0002 secs, 0.0080 secs
  DNS-lookup:	0.0001 secs, 0.0000 secs, 0.0010 secs
  req write:	0.0000 secs, 0.0000 secs, 0.0006 secs
  resp wait:	0.0015 secs, 0.0002 secs, 0.0050 secs
  resp read:	0.0003 secs, 0.0000 secs, 0.0028 secs

Status code distribution:
  [200]	190 responses
  [503]	10 responses

```