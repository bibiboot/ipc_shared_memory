ipc_shared_memory
=================

IPC using Shared memory

Steps to run
------------
- First run the server.
- Then run the client.

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

