# Single V8 instance.
- Single User
  Thread Count: 8 Total Time: 20578 Run Count: 213 Fail Count: 0 Retry Count: 0
- Two User
  Thread Count: 8 Total Time: 21140 Run Count: 93 Fail Count: 0 Retry Count: 0
  Thread Count: 8 Total Time: 21211 Run Count: 89 Fail Count: 4 Retry Count: 4
- Four User
  Thread Count: 8 Total Time: 21532 Run Count: 48 Fail Count: 0 Retry Count: 0
  Thread Count: 8 Total Time: 22309 Run Count: 48 Fail Count: 0 Retry Count: 0
  Thread Count: 8 Total Time: 22535 Run Count: 50 Fail Count: 0 Retry Count: 0
  Thread Count: 8 Total Time: 22548 Run Count: 49 Fail Count: 0 Retry Count: 0

1: 10 cps
2: 4 cps
4: 2.5 cps

# Two V8 instance.
- Single User
  VM0: Thread Count: 8 Total Time: 20578 Run Count: 178 Fail Count: 0 Retry Count: 0
  VM1: Thread Count: 8 Total Time: 20644 Run Count: 183 Fail Count: 0 Retry Count: 0
- Two User
  VM0: Thread Count: 8 Total Time: 21960 Run Count: 95 Fail Count: 2 Retry Count: 2
       Thread Count: 8 Total Time: 22035 Run Count: 99 Fail Count: 0 Retry Count: 0
  VM1: Thread Count: 8 Total Time: 21152 Run Count: 101 Fail Count: 3 Retry Count: 3
       Thread Count: 8 Total Time: 21367 Run Count: 100 Fail Count: 0 Retry Count:  
- Four User
  VM0: Thread Count: 8 Total Time: 21393 Run Count: 32 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 21445 Run Count: 32 Fail Count: 5 Retry Count: 5
       Thread Count: 8 Total Time: 22074 Run Count: 32 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 22380 Run Count: 32 Fail Count: 0 Retry Count: 0 
  VM1: Thread Count: 8 Total Time: 20615 Run Count: 32 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 23123 Run Count: 39 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 23230 Run Count: 38 Fail Count: 5 Retry Count: 5
       Thread Count: 8 Total Time: 23366 Run Count: 40 Fail Count: 0 Retry Count: 0

1: 16 cps
2: 9 cps
4: 3 cps

# Four V8 instance.
- One User
  VM0: Thread Count: 8 Total Time: 24867 Run Count: 54 Fail Count: 0 Retry Count: 0
  VM1: Thread Count: 8 Total Time: 24194 Run Count: 48 Fail Count: 0 Retry Count: 0
  VM2: Thread Count: 8 Total Time: 23979 Run Count: 47 Fail Count: 0 Retry Count: 0
  VM4: Thread Count: 8 Total Time: 22504 Run Count: 40 Fail Count: 0 Retry Count: 0
- Two User
  VM0: Thread Count: 8 Total Time: 25792 Run Count: 40 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 26259 Run Count: 40 Fail Count: 0 Retry Count: 0
  VM1: Thread Count: 8 Total Time: 23315 Run Count: 32 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 24503 Run Count: 32 Fail Count: 0 Retry Count: 0
  VM2: Thread Count: 8 Total Time: 24712 Run Count: 32 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 25049 Run Count: 31 Fail Count: 0 Retry Count: 0
  VM3: Thread Count: 8 Total Time: 20553 Run Count: 24 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 24252 Run Count: 30 Fail Count: 0 Retry Count: 0
- Four User
  VM0: Thread Count: 8 Total Time: 21320 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 22283 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 23210 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 23226 Run Count: 16 Fail Count: 0 Retry Count: 0
  VM1: Thread Count: 8 Total Time: 23110 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 24911 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 25356 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 26533 Run Count: 16 Fail Count: 0 Retry Count: 0
  VM2: Thread Count: 8 Total Time: 26403 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 26836 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 27428 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 28535 Run Count: 16 Fail Count: 0 Retry Count: 0
  VM3: Thread Count: 8 Total Time: 26529 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 27364 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 27682 Run Count: 16 Fail Count: 0 Retry Count: 0
       Thread Count: 8 Total Time: 28067 Run Count: 16 Fail Count: 0 Retry Count: 0

1: 10 cps
2: 6 cps
4: 3 cps

Conclusion: it seems the overall request per second is limited per application, but it may be caused by the proxy server.
