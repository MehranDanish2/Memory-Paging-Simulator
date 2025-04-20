
# 🧠 Virtual Memory Paging Simulator (C++)

A C++ simulation of a virtual memory system using paging and the Least Recently Used (LRU) page replacement algorithm. It handles address translation, page faults, memory allocation, and displays performance stats after simulated memory accesses.

---

## 📘 Overview

This project models how an operating system manages virtual memory using a paging mechanism. It simulates virtual-to-physical address translation, detects page faults, allocates physical frames, and replaces pages using the LRU algorithm.

Key components include:
- Page Table Management
- Frame Table Tracking
- Random Memory Access Simulation
- Page Replacement Handling (LRU)
- Console Reporting of Memory Stats

---

## 📐 System Configuration

| Configuration         | Value          |
|----------------------|----------------|
| Page Size            | 4096 bytes     |
| Physical Memory      | 65536 bytes (64 KB) |
| Virtual Memory       | 131072 bytes (128 KB) |
| Physical Frames      | 16             |
| Virtual Pages        | 32             |

---

## ✨ Features

- ✅ Virtual to Physical Address Translation
- ⚠️ Page Fault Handling
- 🔄 LRU Page Replacement Strategy
- 📌 Referenced & Modified Bit Management
- 📊 Page and Frame Table Display
- 🧪 20 Random Memory Accesses (Read/Write)
- 📈 Performance Statistics (Fault Rate, Usage)

---

## 🛠️ How to Compile & Run

### 🔧 Compile:
```bash
g++ -std=c++11 paging_simulator.cpp -o paging_simulator
▶️ Run:
bash
Copy
Edit
./paging_simulator
🖥️ Output Example
Virtual & Physical Address Mapping

Page Fault Messages

Frame Allocation Logs

Page Replacements with LRU Info

Final Page Table & Frame Table Display

Page Fault Rate Summary

📚 Educational Use
This simulator is perfect for:

Operating Systems coursework

Visualizing memory management

Learning about paging & LRU in C++

📄 License
Licensed under the MIT License.

🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request for improvements or feature ideas.

📬 Contact
For issues, suggestions, or questions, feel free to open an issue on the GitHub repository.

