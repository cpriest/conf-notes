Typical Size: 1TB to 200TB



```
			    Proxy		Proxy if desired
                 /\
TiDB Node(s)	1  2		Talk to any head
  |    |	   /|  |\		Uses Raft
TiKV Node(s)  1 2  3 4		RocksDB
  |    |      | |  | |
Disk  Disk	  D D  D D 		Disks/Volumes
```
