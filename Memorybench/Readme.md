
```
# The unit is GB here for the size
python membench.py --size 10
numactl --cpunodebind=0 python membench.py --size 10


# p.s.: also a efficient way to check if the isolation of CPU cores works
```
