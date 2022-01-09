# 3301 Twitter Investigation

Summary:
```An investigation into if they is any hidden secrets within the username of 3301.```

Information:
```
Username:   1231507051321
Link:       https://twitter.com/1231507051321
```

Pattern #1:
```
      o
    o   o
  o   o   o
      o
  o o o o o
o o o o o o o
  o o o o o
      o
  o   o   o
    o   o
      o
```

> When we drop {1 2 3 `1` 5 `0` 7 `0` 5 `1` 3 2 1} (the high-lighted values) we are left with: `123575321` - *PRIME/EMIRP/PALINDROMIC*

Pattern #2 (Removal of non primes leaving only one non-prime value at the start/end):
```
      o
    o   o
  o   o   o
  o o o o o
o o o o o o o
  o o o o o
  o   o   o
    o   o
      o
```

Pattern #3 (Pattern #2 Rotated):
```
        o
    o o o o o
  o   o o o   o
o   o o o o o   o
  o   o o o   o
    o o o o o
        o
```

> The values are then transformed into `1557551` - *PRIME/EMIRP/PALINDROMIC*

Attempt Ideas:
```
123575321 * 1557551 * 3301    =     635359528701073000      (.com) - DEAD LINK
123575321 - 1557551 * 3301    =     402780658770            (.com) - DEAD LINK
123575321 + 1557551 * 3301    =     413063610472            (.com) - DEAD LINK
123575321 - 1557551 - 3301    =     122014469               (.com) - DEAD LINK
123575321 + 1557551 + 3301    =     125136173               (.com) - DEAD LINK
123575321 - 1557551 * 1033    =     126044356410            (.com) - DEAD LINK
123575321 + 1557551 * 1033    =     129262256776            (.com) - DEAD LINK
123575321 - 1557551 - 1033    =     122016737               (.com) - DEAD LINK
123575321 + 1557551 + 1033    =     125133905               (.com) - DEAD LINK
123575321 * 1557551 * 1033    =     198826535337234000      (.com) - DEAD LINK
``` 
