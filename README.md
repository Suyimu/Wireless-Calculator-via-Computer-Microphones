# Wireless Calculator via Computer Microphones 🎧➗📡
## Acoustic Data Communication
### Description
This project establishes a communication system between two computers using their microphones and speakers, effectively creating a wireless calculator. The system allows one computer to send a mathematical expression to another, which computes the result and sends it back. This process is robust even in noisy environments due to specific noise handling technologies.

**Features:**
- **Transmission using 2FSK modulation:** Allows for efficient and reliable data transfer.
- **Error Handling with Hamming Code:** Automatic error correction is enabled by using (7,4) Hamming code.
- **High Data Rate:** Achieves data transmission rates up to 200 bits per second, with potential to reach 400 bits per second.
- **Frame Synchronization:** Utilizes Barker code for frame synchronization, enhancing the reliability of transmission.
- **Robust to Noise:** Designed to handle significant noise levels, suitable for real-world environments.

### System Setup
- **Hardware:** Two standard PCs with low-quality headsets.
- **Software:** MATLAB.
- **OS:** Windows 10.

### Usage
1. Ensure audio settings are configured to disable audio enhancements to prevent automatic filtering of high frequencies.
2. Run the MATLAB scripts on both sending and receiving computers.

### Credits
Developed under the guidance of Professor Hou and inspired by the code and approaches shared by senior student Wang Yafei.

---

## 无线计算器 —— 通过计算机麦克风通信

### 描述
本项目通过两台计算机的麦克风和扬声器建立通信系统，实现无线计算器功能。系统允许一台计算机向另一台发送数学表达式，接收端计算结果后返回。该系统即使在噪声环境下也能稳定运行，这得益于特定的噪声处理技术。

**特点:**
- **使用2FSK调制传输:** 确保数据传输的效率和可靠性。
- **汉明码错误处理:** 通过使用(7,4)汉明码实现自动错误纠正。
- **高数据传输率:** 数据传输速率可达每秒200比特，理论上可达400比特。
- **帧同步:** 使用巴克码进行帧同步，提高传输可靠性。
- **抗噪声:** 设计能够处理较大的噪声水平，适合真实环境。

### 系统设置
- **硬件:** 两台标准个人电脑，低质量耳机各一副。
- **软件:** MATLAB。
- **操作系统:** Windows 10。

### 使用方法
1. 确保音频设置中禁用音频增强，以防止自动过滤高频。
2. 在发送和接收计算机上运行 MATLAB 脚本。

### 鸣谢
在侯老师的指导下开发，并受到学长王亚飞分享的代码和方法的启发。
