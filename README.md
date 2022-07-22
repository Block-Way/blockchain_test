
## Node synchronization test

### testing procedure
```bash
#Start the server side
./test_sync_node -port=2000

#Start client
./test_sync_node -addnode=127.0.0.1:2000 -sendpush=-1
```

### View statistics
```bash
#...
#17:33:27.007529|main:info|test_sync_node|node: 1, sync: 16438600 : 1321120

# node：Indicates the number of connected nodes
# sync：The first is the total data received, and the second is the data per second
```
