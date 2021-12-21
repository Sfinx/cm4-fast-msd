Usage:
------

```
git clone https://github.com/sfinx/cm4-fast-msd
cd cm4-fast-msd
rpiboot -d .
```

```
# dd if=/dev/sdxx of=/dev/null bs=1M
1024+0 records in
1024+0 records out
1073741824 bytes (1,1 GB, 1,0 GiB) copied, 33,7255 s, 31,8 MB/s

# dd if=/dev/zero of=/dev/sdxx bs=1M
dd: error writing '/dev/sdd1': No space left on device
1025+0 records in
1024+0 records out
1073741824 bytes (1,1 GB, 1,0 GiB) copied, 39,8048 s, 27,0 MB/s
```
