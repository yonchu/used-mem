used-mem
=======================

Print memory status for Mac OSX and Linux.

Usage
-----------------------

```console
used-mem [Output format]
```

Format string:

- ``#f`` : Free memory(%).
- ``#u`` : Used memory(%).
- ``#F`` : Free memory(GB).
- ``#U`` : Used memory(GB).
- ``#T`` : Total memory(GB).


Sample
-----------------------

```console
$ used-mem
77.8%(6.2G/8.0G)

$ used-mem '#f%(#FG/#TG)'
22.2%(1.8G/8.0G)

```
