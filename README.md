# Hi, I'm Benoît 👋

Embedded software engineer from Switzerland. I started as an electronics
technician (Swiss CFC), worked in R&D and test on atomic clocks at Safran
Timing Technologies, then completed a Bachelor in Computer Science and
Communication Systems at HEIG-VD (2026).

I like working where software meets the hardware: C and C++ on
microcontrollers, real-time operating systems, embedded Linux, and the
electronics around them. I currently work as a full stack developer at the
University of Lausanne.

📍 Open to embedded / software roles in Switzerland, Germany and the Nordics.

## What I work with

**Languages:** C, C++, Python, Java, C#, TypeScript
**Embedded:** Zephyr, Mbed-OS, Xenomai, Linux drivers, cross-compilation, JTAG
**Hardware:** PCB design (Altium Designer), FPGA (VHDL), lab instruments
**Tools:** Linux, Git, Docker, CI

## Projects

### 📡 [Nanostack on Zephyr RTOS](https://github.com/Travail-de-Bachelor-Delay-Benoit/zephyr-nanostack) (Bachelor thesis)
Port of Arm's Nanostack (the Wi-SUN / 6LoWPAN mesh stack from Mbed OS) to
Zephyr, as an external Zephyr module.
- Rewrote the system layer with Zephyr primitives: stack timer, critical
  sections, hardware RNG, event loop in its own thread
- Connected the stack to Zephyr's Ethernet and IEEE 802.15.4 sub-GHz drivers
  through AF_PACKET sockets, and its AES-CCM and EAP-TLS calls to Mbed TLS
- Ethernet bridge working (SLAAC, ping6, TCP server), radio frames exchanged
  between two TI CC1352P7 boards. Full Wi-SUN network not validated on
  hardware yet
- Found a bug in Zephyr's TI CC13xx radio driver (only channel 0 gets the
  right frequency)

`C` `Zephyr` `west` `CMake/Kconfig` `Mbed TLS` `STM32F769I-DISCO` `CC1352P7`

### 🕹️ [CHIP-8 emulator](https://github.com/Karilla/chip-8-emulator)
CHIP-8 interpreter in C11, with a step-by-step debugger that shows the
decoded instruction, registers, stack and timers. Separate CPU and timer
clocks, XOR sprite drawing with collision flag, memory dump.

`C11` `raylib` `raygui` `CMake`

### 🧱 [Atelier](https://github.com/Karilla/Atelier) (in progress)
Small educational 3D engine in C++ and OpenGL, built milestone by milestone,
with a platformer developed alongside to test each feature. So far: RAII
wrappers for OpenGL objects (shaders, textures, buffers, vertex arrays), a
small logger, OpenGL debug output, and a renderer so the game code makes no
direct OpenGL calls. The basics follow the LearnOpenGL tutorial.

`C++` `OpenGL` `GLFW` `GLM` `CMake`

### 🧭 [Raycasting engine](https://github.com/Karilla/raycasting)
Pseudo-3D renderer in the style of Wolfenstein 3D: DDA ray casting on a grid,
fisheye correction, textured walls, 2D minimap, movement with simple
collision.

`C` `raylib` `Make`

### 🔥 [Bâton Bagarre](https://github.com/Raynobrak/baton-bagarre-game) (team project, 4 people)
2D action game made in three weeks at HEIG-VD:
waves of enemies while the light fades with th
system, the options menu with volume sliders,
increasing difficulty, and the GitHub Actions

`Python` `PyGame` `GitHub Actions`

## Contact

[LinkedIn](https://www.linkedin.com/in/benoit-
benoit.delay@proton.me
