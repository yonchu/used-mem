used-mem
=======================

Print memory status for Mac OSX and Linux.

```console
$ used-mem
77.8%(6.2G/8.0G)

$ used-mem '#f%(#FG/#TG)'
22%(2G/8G)

$ used-mem 'Free: #.2f % (#.3F GB) | Used: #.2u % (#.3U GB) | Total: #.3T GB'
Free: 38.32 % (3.065 GB) | Used: 61.68 % (4.933 GB) | Total: 7.998 GB
```

Usage
-----------------------

```
used-mem [Output format]
```

Default format:

- ``#.1u%(#.1UG/#.1TG)``

Format string:

- ``#f`` : Free memory(%).
- ``#u`` : Used memory(%).
- ``#F`` : Free memory(GB).
- ``#U`` : Used memory(GB).
- ``#T`` : Total memory(GB).

Use on tmux or screen
-----------------------

Used memory(%\):

![sample01](https://raw.github.com/yonchu/used-mem/master/img/used-mem01.png)


Used memory(%)(GB) and total memory(GB):

![sample02](https://raw.github.com/yonchu/used-mem/master/img/used-mem02.png)


Used memory(%)(GB) and free memory(%)(GB):

![sample03](https://raw.github.com/yonchu/used-mem/master/img/used-mem03.png)

