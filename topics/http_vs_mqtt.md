---
marp: true
theme: default
paginate: true
---

# IoT Sensor Communication  
## HTTP vs MQTT  
Alykaa Salaah  

---

# What I Learned

- IoT devices need a way to send data
- Different protocols are used depending on the situation
- Two common ones are:
  - HTTP
  - MQTT

---

# What is HTTP?

- HTTP = HyperText Transfer Protocol  
- Used by websites and APIs  
- Works with request, this goes to, response  

Example:
- Device sends data to server
- Server responds back

---

# How I Used HTTP

- My ESP32 sends sensor data using HTTP POST  
- Python server receives the data  
- Data is stored and displayed on dashboard  

---

# Why HTTP is Useful

- Easy to understand and use  
- Works well with web apps  
- Supported everywhere  

---

# Limitations of HTTP

- Requires constant requests  
- Not very efficient for frequent data  
- Slightly slower for real-time systems  

---

# What is MQTT?

- MQTT = Message Queuing Telemetry Transport  
- Lightweight protocol for IoT  
- Uses publish/subscribe model  

---

# How MQTT Works

- Device publishes data to a topic  
- Server or app subscribes to that topic  
- Data is sent instantly when available  

---

# Why MQTT is Better for IoT

- Faster and lightweight  
- Uses less bandwidth  
- Better for real-time updates  
- More scalable for many devices  
