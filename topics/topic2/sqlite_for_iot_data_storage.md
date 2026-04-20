---
marp: true
theme: default
paginate: true
---

# SQLite for IoT Data  
## Storage & Time-Series Queries  
Alykaa Salaah  

---

# What I Learned

- IoT systems generate continuous data  
- This data needs to be stored and accessed  
- Databases help organize and retrieve data  

---

# What is SQLite?

- Lightweight database  
- Stored as a single file  
- No server required  

---

# How I Used SQLite

- My Python server stores sensor data  
- Data includes:
  - Soil moisture  
  - Temperature  
  - Humidity  
  - Timestamp  

---

# Example Data

| Time | Soil | Temp | Humidity |
|------|------|------|----------|
| 2:00 | 30% | 21°C | 40% |
| 2:05 | 28% | 21°C | 41% |

---

# What is Time-Series Data?

- Data collected over time  
- Each entry has a timestamp  
- Used to track changes  

---

# Time-Series Queries

Examples:
- Get latest data  
- Get last 10 readings  
- Track trends over time  

---

# Why This Matters

- Helps visualize plant health  
- Shows patterns (drying over time)  
- Supports better decision-making  

---

# Why SQLite is Good

- Simple to set up  
- No external server needed  
- Fast for small projects  
- Works well with Python  

---

# Limitations

- Not ideal for large-scale systems  
- Limited performance with many users  
- Not cloud-based by default  

---

# How This Helped My Project

- Stored real sensor data  
- Allowed dashboard to show history  
- Enabled graphs and trends  

---

# Future Improvements

- Move to cloud database  
- Handle more devices  
- Store more detailed data  

---

# Key Takeaway

- SQLite is great for small IoT projects  
- Time-series data is essential for understanding trends  
