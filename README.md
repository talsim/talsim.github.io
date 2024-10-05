# 🧑‍💻 About Me 

Hey there! I'm **Tal Simhayev** 👋

I'm a passionate Security Researcher focused on:
* **Reverse engineering**, exploit development, and vulnerability discovery 🔍
* Low-level system programming using **C/C++**, and **Python** 💻
* **Tools:** Ghidra, **IDA Pro**, Radare2, **GDB**, pwntools, and x86/x64 Assembly 🛠️

I've been programming since age 10, and over the years, I’ve developed a strong understanding of **Linux internals**, **binary exploitation** and **exploit development**.  

I've also participated in lots of **CTF** events with my [team](https://github.com/C0d3-Bre4k3rs), primarily focused in categories like **binary exploitation** and **reverse engineering**.  
These challenges helped me gain hands-on experience while collaborating with my team under pressure to bypass modern defenses like **ASLR**, **DEP**, and **PIE**.

🔒 **My goal** is to continue pushing the boundaries in **cybersecurity** and contribute to safer systems worldwide.


# Projects

### 🐄 [Exploited Dirty COW (CVE-2016-5195)](https://github.com/talsim/root-dirtyc0w)

* **Privilege escalation vulnerability** in the Linux Kernel 🐧

* **Tools Used:** C, Linux Kernel

* Successfully crafted a PoC that exploits a race-condition in the kernel to achieve **root access**.


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
I document my CTF Experience [here](https://github.com/talsim/CTFs). Below are some of my notable write-ups:
### 🛠️ [pingCTF 2023 dangle-me pwn challenge write-up](https://ctftime.org/writeup/38337)
* Developed a working exploit for a memory corruption vulnerability

* Focused on **stack-based buffer overflows** and **Return Oriented Programming (ROP)** techniques

* Bypassed **PIE Mitigation** by **leaking addresses** from process memory
  
* Check out the exploit on [Github](https://github.com/talsim/CTFs/tree/main/pingCTF-2023/dangle_me).

<div align="center">
  <div style="border: 1px solid #ccc; display: inline-block; padding: 5px;">
    <img src="/assets/gifs/dangle-me.gif" alt="dangle-me PoC GIF" width="1500px" style="display: block; border: none;">
  </div>
  <p style="margin-top: 5px;"><em>pingCTF 2023 dangle-me PoC demo</em></p>
</div>

### 📝 [ROP Emporium write4 - Blog](https://thehackerlife.medium.com/rop-emporium-write4-challenge-writeup-64-bit-updated-2020-742eab2722ec)

* Crafted an **arbitrary write exploit** (write-what-where condition) to **inject data** to memory and bypass **DEP** protection mechanism

* Published on Medium, it showcases **how to chain ROP gadgets** effectively.

<div align="center">
  <img src="/assets/gifs/write4.gif" alt="write4 PoC GIF" width="70%">
  <p><em>ROP Emporium write4 PoC demo</em></p>
</div>

 
# 📧 Contact & Resume

You can download my **CV [here](/assets/resume/Tal-Simhayev-CV.pdf)** for a detailed overview of my experience, or contact me via email at **[talsimhayev@gmail.com](mailto:talsimhayev@gmail.com)**.

Feel free to connect with me on:  
[![GitHub](https://img.shields.io/badge/GitHub-black?style=flat&logo=github)](https://github.com/talsim)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://linkedin.com/in/talsim)
