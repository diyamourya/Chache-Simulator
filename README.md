# Chache-Simulator
# Abstract
Speed is the major limiting factor for the performance of the com-
puter with which the data can be moved between processor and mem-
ory. So cache memory was placed between the main memory and
processor. Several mapping techniques were used to map data into
cache memory. Since L1 cache is direct mapped it has one-to-one re-
lation, different address of data will conflict for same location in L1
cache and hence there is a miss called conflict misses which leads to
miss penalty thus decreasing the performance.
In this project, a new two cache schemes like victim cache and
skewed associative cache were implementeted and compared with the
help of verilog and code in suitable programing language to compare
the cache based enhancements. Victim cache is fully associative cache
and its size is small compared to L1 cache, it is placed next to L1
instruction cache to hold the evicted block because of conflict miss or
replaced block from L1 cache. Another new cache scheme is skewed
associative cache, where two mapping function is used to map the
address into different banks with different location which is unlike in
conventional cache scheme.
