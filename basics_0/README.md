# Task 0: OSI Model

## What is the OSI model?
The OSI model (Open Systems Interconnection) is a **conceptual model** that characterizes the communication functions of a telecommunication system **without regard to their underlying internal structure and technology**.  
It helps to understand complex networking processes by **dividing them into seven layers**:

1. **Physical** – Transmission of raw bits via electrical, light, or radio signals.
2. **Data Link** – MAC addresses and frame formatting.
3. **Network** – IP addressing, routing.
4. **Transport** – TCP/UDP, reliable or fast data delivery.
5. **Session** – Managing sessions or connections.
6. **Presentation** – Data formatting and encryption.
7. **Application** – Applications like HTTP, SNMP, email, web browsers.

> Note: This project mainly focuses on the **Transport layer (TCP/UDP)** and **Network layer (IP/ICMP)**.

## How is the OSI model organized?
The OSI model is organized **from the lowest to the highest level**, starting at the Physical layer (Layer 1) and ending at the Application layer (Layer 7).

## Bash Script
The `0-OSI_model` bash script prints the questions and answers for this task.  
Run it using:
```bash
chmod +x 0-OSI_model
./0-OSI_model
