# Single Room Multi User Chat Application

The application is built using the concepts of socket programming and multi-threading in C++. Multiple users can able to communicate in a single room at the same time. 


## How to run

1. First we need to compile both the server and client program. For that run the following command :
```
g++ server.cpp -lpthread -o server
g++ client.cpp -lpthread -o client
```
2. We can run server application using the following command :
```
./server
```

3. In a seperate terminal window, run the following command for client application :
```
./client
```

4. We can able to create multiple clients by repeating step 3.