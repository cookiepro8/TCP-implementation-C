# TCP Client-Server Program in C

A simple TCP socket programming project in C demonstrating communication between a client and server using IPv4 and TCP protocol.

---

## Features

- TCP communication
- Client-server architecture
- Message sending and receiving
- Uses sockets in C
- Works on Linux

---

## Files

### `server.c`
Creates a TCP server that:
- Listens on port 8080
- Accepts client connections
- Receives messages
- Sends response back

### `client.c`
Creates a TCP client that:
- Connects to server
- Sends message
- Receives server response

---

## Technologies Used

- C Programming
- Linux Socket Programming
- TCP/IP
- GCC Compiler

---

## Compilation

### Compile Server

```bash
gcc server.c -o server
```

### Compile Client

```bash
gcc client.c -o client
```

---

## Running the Project

### Step 1: Run Server

```bash
./server
```

### Step 2: Run Client

Open another terminal and run:

```bash
./client
```

---

## Expected Output

### Server

```text
Server waiting...
Client says: Hello from client
```

### Client

```text
Hello message sent
Server Response: Hello from server
```

---

## Concepts Covered

- Socket Creation
- TCP Connections
- IP Addressing
- Port Communication
- Sending and Receiving Data

---

## Author

Abdul Razzak
