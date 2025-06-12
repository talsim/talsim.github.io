# About Me 

Hey there! I'm **Tal Simhayev** 👋

I like to participate in **CTF** events with my [team](https://github.com/C0d3-Bre4k3rs), mainly focused in categories like **binary exploitation** and **reverse engineering** (Scored **18th place** in pingCTF-2023 - See below).  
In these challenges I collaborated with my team under pressure to bypass modern defenses like **ASLR**, **DEP**, and **PIE**.

# Projects

### 🐄 [Exploited Dirty COW (CVE-2016-5195)](https://github.com/talsim/root-dirtyc0w)

* **Privilege escalation vulnerability** in the Linux Kernel 🐧

* **Tools Used:** C, Linux Kernel

* Successfully crafted a PoC that exploits a race-condition in the kernel to achieve **root access**.

<div align="center">
  <div style="border: 2px solid #ccc; display: inline-block; padding: 6px;">
    <img src="/assets/gifs/root-dirtyc0w.gif" alt="root-dirtyc0w PoC GIF" style="display: block; border: none;">
  </div>
  <p style="margin-top: 6px;"><em>Privilege Escalation PoC: Exploiting Dirty COW for Root Access (CVE-2016-5195)</em></p>
</div>

### 🐴 [CloakRAT](https://gitHub.com/talsim/CloakRAT) (Work in Progress)
* **Remote Access Trojan (RAT)** written in **C++**.
* **Evades AV detection** and maintains **persistence** on the target machine.
* Injects itself to processes using **DLL Injection**.
* Implements **anti-debugging** techniques and **C2 Communication**.


### 🔑 [KeyLogger (C/C++)](https://github.com/talsim/Keylogger)
* Used **Windows Hooking API** to log keystrokes 📃
* Implemented persistence through Windows Registry modifications 🗝️


### 🖥️ [Implemented Linux shell](https://github.com/talsim/Linux-Shell)
* Custom-built shell in **C**.
* A deep dive into **Linux Internals**.


### 🔢 [HashMap](https://github.com/talsim/Cpp-HashMap) & [LinkedList](https://github.com/talsim/c-linked-list) in C/C++
* Implemented core data structures like **HashMap** and **LinkedList** in C/C++ for efficiency and memory management (Used when I implemented a shell in Linux).

# CTF Write-ups & Blogs
I regularly participate in **CTF events** with my team, [C0d3-Bre4k3rs](https://github.com/C0d3-Bre4k3rs), where I focus on **binary exploitation** and **reverse engineering**.  
Below are some of my notable write-ups:

### 🔎 [Flare-On 2024 Write-ups](https://github.com/talsim/CTFs/tree/main/Flareon-2024)
* Documented solutions for **4 challenges** from the Flare-On 2024 CTF.
  
* Focused on **reverse engineering** and **binary analysis** techniques.

### 🛠️ [pingCTF 2023 dangle-me pwn challenge write-up](https://ctftime.org/writeup/38337)
* Developed a working exploit for a memory corruption vulnerability

* Focused on **stack-based buffer overflows** and **Return Oriented Programming (ROP)** techniques

* Bypassed **PIE Mitigation** by **leaking addresses** from process memory
  
* Check out the exploit on [Github](https://github.com/talsim/CTFs/tree/main/pingCTF-2023/dangle_me).

<div align="center">
  <div style="border: 2px solid #ccc; display: inline-block; padding: 6px;">
    <img src="/assets/gifs/dangle-me.gif" alt="dangle-me PoC GIF" width="3000px" style="display: block; border: none;">
  </div>
  <p style="margin-top: 6px;"><em>pingCTF 2023 dangle-me PoC</em></p>
</div>

### 📝 [ROP Emporium write4 - Blog](https://thehackerlife.medium.com/rop-emporium-write4-challenge-writeup-64-bit-updated-2020-742eab2722ec)

* Crafted an **arbitrary write exploit** (write-what-where condition) to **inject data** to memory and bypass **DEP** protection mechanism

* Published on Medium, it showcases **how to chain ROP gadgets** effectively.

<div align="center">
  <div style="border: 2px solid #ccc; display: inline-block; padding: 6px;">
    <img src="/assets/gifs/write4.gif" alt="write4 PoC GIF" style="display: block; border: none;">
  </div>
  <p style="margin-top: 6px;"><em>ROP Emporium write4 PoC</em></p>
</div>
 
# 📧 Contact

Feel free to connect with me on:  
[![GitHub](https://img.shields.io/badge/GitHub-black?style=flat&logo=github)](https://github.com/talsim)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://linkedin.com/in/talsim)
