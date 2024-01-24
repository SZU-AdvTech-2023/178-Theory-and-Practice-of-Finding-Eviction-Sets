###  链接（初始化）

make

### 清除

make clean

### 执行

sudo ./evsets -b 3000 -c 6 -s 8 -a g -e 2 -n 12 -o 4096 -r 10 -t 95 -C 0

```
-b N number of lines in initial buffer
-t N threshold in cycles
-c N cache size in MB
-s N number of cache slices
-n N cache associativity
-o N stride for blocks in bytes
-a n|o|g|l search algorithm
-e 0|1|2|3|4 eviction strategy: 0-haswell, 1-skylake, 2-simple
-C N page offset
-r N numer of rounds per test
-q N ratio of success for passing a test
```

