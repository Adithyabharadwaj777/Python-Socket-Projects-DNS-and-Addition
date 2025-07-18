# Python Socket Projects – DNS Resolver, Addition, and CRC Communication

This repository contains three beginner-friendly **client-server projects** implemented using Python’s built-in `socket` library. Each project demonstrates a different concept in socket programming and networking.

---

##  Project 1: TCP Client-Server Addition

**Purpose:** Client sends two numbers, and the server returns their sum.

###  Files:
- `addition/client_add.py` – Takes user input and sends it to the server.
- `addition/server_add.py` – Receives numbers, adds them, and returns the result.

---

##  Project 2: DNS Resolver using Socket

**Purpose:** Client sends a domain name, and the server returns the resolved IP address using Python’s DNS functions.

###  Files:
- `dns_resolver/client_dns.py` – User inputs domain name (e.g., `openai.com`)
- `dns_resolver/server_dns.py` – Resolves domain using `socket.gethostbyname()`

---

##  Project 3: Client-Server with CRC (Cyclic Redundancy Check)

**Purpose:** Demonstrates how **CRC** can be used to detect data errors in client-server communication. The client sends a data message, the server computes CRC to validate its integrity and responds accordingly.

###  Files:
- `crc/client_crc.py` – Sends a message string and its CRC value.
- `crc/server_crc.py` – Receives the data, recomputes the CRC, and checks for errors.

**What is CRC?**  
CRC (Cyclic Redundancy Check) is an error-detecting code commonly used in digital networks and storage devices to detect accidental changes to raw data. In this project, it's used to validate that the message received is intact and uncorrupted.

---

##  How to Run Each Project

> Make sure you have **Python 3.x** installed and use separate terminals for server and client.

### 🔹 Addition Project:
```bash
# Terminal 1
cd addition
python server_add.py

# Terminal 2
cd addition
python client_add.py
