[KiXtart](http://kixtart.org/)

[Benchmark](./benchs.txt)
```
--------------------------------------
BENCH_SMALLSTRINGREPEATING
00:00:00.003ms in O(n²) | bench_smallStringRepeating()
00:00:00.003ms in O(n) | bench_smallStringRepeating()
00:00:00.000ms in O(n)  | small alocation | bench_smallStringRepeating()
--------------------------------------
BENCH_SMALLSTRINGREPEATING
00:00:00.007ms in O(n²) | bench_smallStringNonRepeating()
00:00:00.003ms in O(n) | bench_smallStringNonRepeating()
00:00:00.000ms in O(n)  | small alocation | bench_smallStringNonRepeating()
--------------------------------------
BENCH_LARGESTRINGREPEATING
00:00:06.859ms in O(n²) | bench_largeStringRepeating()
00:00:00.592ms in O(n) | bench_largeStringRepeating()
00:00:00.247ms in O(n)  | small alocation | bench_largeStringRepeating()
--------------------------------------
BENCH_LARGESTRINGNONREPEATING
00:00:01.650ms in O(n²) | bench_largeStringNonRepeating()
00:00:00.396ms in O(n) | bench_largeStringNonRepeating()
00:00:00.061ms in O(n)  | small alocation | bench_largeStringNonRepeating()
```