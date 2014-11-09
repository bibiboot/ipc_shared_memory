ipc_shared_memory
=================

IPC using Shared memory

Author
-----
Love barista

Server
-----
```
    gcc -o cli shm-client.c -lpthread
```

Client
------
```
    gcc -o ser shm-server.c -lpthread
```

Steps to run
------------
- First run the server.
  ```
      ./ser
  ```
- Then run the client.
  ```
      ./cli
  ```

Expected outout
--------------
- The client will print the message written in memory by the server.


