# Python Socket Projects – DNS Resolver & Addition Server

This repository contains two beginner-friendly **client-server projects** implemented using Python’s built-in `socket` library:

---

##  Project 1: TCP Client-Server Addition

**Purpose:** Client sends two numbers, and the server returns their sum.

###  Files:
- `addition/client_add.py` – Takes user input and sends to server.
- `addition/server_add.py` – Waits for client, adds two numbers, returns the result.

---

##  Project 2: DNS Resolver using Socket

**Purpose:** Client sends a domain name, and the server returns the resolved IP address using Python’s DNS functions.

###  Files:
- `dns_resolver/client_dns.py` – User inputs domain name (e.g., `google.com`)
- `dns_resolver/server_dns.py` – Resolves IP using `socket.gethostbyname()`

---

##  How to Run

### Start the Server:
```bash
python server_add.py       # For addition project
python server_dns.py       # For DNS resolver project
