# computer-networks
# 🖥️ Computer Networking

Computer networking means connecting two or more computers or devices so they can **share data, files, and resources** with each other.

---

## 🌐 Types of Computer Networks

There are **5 main types** of networks:

---

### 1️⃣ Personal Area Network (PAN)

- Small network centered on **one person**  
- Connects devices: smartphones, laptops, tablets, earphones, smartwatches  
- Range: **less than 10 meters**  
- Used in a **room or small personal space**

**Example:** Connecting phone to Bluetooth earphones

---

### 2️⃣ Local Area Network (LAN)

- Bigger than PAN  
- Covers a **small area** (home, school, office, building)  
- Connects PCs, printers, servers  
- Limited to that local area

**Example:** Computers connected in a school computer lab

---

### 3️⃣ Campus Area Network (CAN)

- Bigger than LAN  
- Covers **multiple buildings** inside a campus  
- Connects multiple LANs  
- Managed by a single organization

**Example:** University connecting all departments

---

### 4️⃣ Metropolitan Area Network (MAN)

- Bigger than CAN  
- Covers a **city or large town**  
- Connects multiple LANs and CANs  
- Used by ISPs, government, telecom services

**Example:** City-wide broadband network

---

### 5️⃣ Wide Area Network (WAN)

- Largest network  
- Covers **countries, continents, world**  
- Connects multiple LANs, CANs, and MANs  
- The **Internet** is the biggest WAN

**Example:** Banks connecting branches worldwide

---

## ✅ Summary Table

| Network Type | Coverage Area | Example |
|--------------|----------------|---------|
| PAN | Very small (1 person) | Bluetooth devices |
| LAN | Home/office building | School lab network |
| CAN | Campus area | University network |
| MAN | City area | City-wide ISP |
| WAN | Global | Internet |

# 🌐 IP Address Basics (IPv4, Public, Private, Localhost)

An **IP Address (Internet Protocol Address)** is a unique number given to every device in a network so it can **communicate and transfer data**.

---

## 🔢 1. IPv4 (Internet Protocol Version 4)

- IPv4 is the **most commonly used** version of IP.  
 
- Range: **0.0.0.0 to 255.255.255.255**  
 

**Example IPv4 address:**  
`192.168.1.10`

**Format:**  
`A.B.C.D` (each section = 0 to 255)

---

## 🏠 2. Private IP Address

Private IPs are used **inside local networks** (home/office).  
They **cannot** be accessed directly from the internet.

**Common Private IP Ranges:**

| Class | Private Range |
|--------|----------------|
| Class A | 10.0.0.0 – 10.255.255.255 |
| Class B | 172.16.0.0 – 172.31.255.255 |
| Class C | 192.168.0.0 – 192.168.255.255 |

**Example:**  
`192.168.1.5` (your Wi-Fi PC or phone)

---

## 🌍 3. Public IP Address

Public IP is provided by your **Internet Service Provider (ISP)**.  
It is used to communicate with devices **across the internet**.

- Unique globally  
- Websites, servers, routers use it  
- Visible to the outside world

**Example:**  
`103.45.67.89`

> Your home router has a **public IP**, but the devices inside your home get **private IPs**.

---

## 🔁 4. Localhost (127.0.0.1)

`127.0.0.1` is called **localhost**.  
It refers to **your own computer**.

- Used for testing servers locally  
- No internet required  
- Always points to the same device

**Example:**  
Typing `http://localhost:3000` runs your local project.

---

## ✔ Summary

| Type | Example | Used For |
|------|---------|----------|
| IPv4 | 192.168.1.10 | Standard IP format |
| Private IP | 192.168.0.10 | Devices inside home/office |
| Public IP | 103.45.67.89 | Internet communication |
| Localhost | 127.0.0.1 | Testing on same machine |
# 📘 Network Topologies – Beginner Notes

## 1. What is Network Topology?
Network topology refers to the **physical or logical arrangement** of computers, cables, and network devices.  
It defines **how devices are connected** and **how data flows** in a network.

Topologies affect:
- Network speed  
- Performance  
- Reliability  
- Cost  
- Ease of management  

---

## 2. Types of Network Topologies

### 🟦 1. Bus Topology
- All devices share a **single central cable** (bus).
- Simple and inexpensive for small networks.

**Performance Impact:**
- Slow when traffic is high.
- If the bus cable fails, the entire network stops.

---

### ⭐ 2. Star Topology
- Every device connects to a **central device** (switch/hub).
- Most common in modern networks.

**Performance Impact:**
- Fast due to dedicated connections.
- If the central device fails, the whole network goes down.

---

### 🔴 3. Ring Topology
- Devices are connected in a **loop** (ring).
- Data flows in one direction around the ring.

**Performance Impact:**
- Predictable performance.
- Failure of one device breaks the entire ring.

---

### 🟢 4. Mesh Topology
- Each device connects to **multiple devices**.
- Used in critical and large networks.

**Performance Impact:**
- Very high reliability and speed.
- Failure of one link does not affect the network.
- Very costly due to many cables.

---

### 🟡 5. Tree (Hierarchical) Topology
- A combination of multiple star topologies in a **tree structure**.
- Suitable for large organizations.

**Performance Impact:**
- Easy to expand and manage.
- Failure of a main node affects all devices in its branch.

---

### 🟣 6. Hybrid Topology
- Mix of multiple topologies (e.g., Star + Mesh).
- Highly flexible and scalable.

**Performance Impact:**
- High performance and reliability.
- More complex and expensive.

---

## 3. Quick Comparison Table

| Topology | Cost | Speed | Reliability | Best Use |
|----------|------|--------|-------------|----------|
| **Bus** | Low | Low | Low | Small networks |
| **Star** | Medium | High | Medium | Homes & offices |
| **Ring** | Medium | Medium | Low | Legacy networks |
| **Mesh** | High | Very High | Very High | Backbone, telecom |
| **Tree** | Medium | High | Medium | Large organizations |
| **Hybrid** | High | High | High | Enterprise networks |

---

## 4. Summary for Beginners
- **Star Topology** → Fast, reliable, and most widely used.  
- **Mesh Topology** → Best performance but expensive.  
- **Bus Topology** → Outdated and slow.  
- **Ring Topology** → Rare today.  
- **Tree & Hybrid** → Ideal for large, scalable networks.

---

If you want, I can also:
✅ Add diagrams  
✅ Make a PDF  
✅ Convert into a GitHub wiki page  
Just tell me!  

