<details>
<summary>ENG (English Version)</summary>

## **Chapter 4 – Computer Architecture**  

This chapter provides an overview of computer architecture, explaining how computers process and execute instructions, manage memory, and organize internal components such as the CPU, buses, and storage hierarchy.

### **1. Von Neumann Architecture and Stored Program Concept**  
Introduces the **stored-program concept** proposed by John von Neumann, where both data and instructions are stored in the same memory. The CPU sequentially fetches, decodes, and executes these instructions, enabling programmable and automated computing.

### **2. Instruction Structure and Machine Languages**  
Describes the format of an instruction: **operation part (opcode)** and **operand part (address)**. Instructions are often 16 bits, divided into 4-bit operation codes and 12-bit address fields. Basic operations include ADD, LOAD, STORE, and HALT. Also explains **machine language** (binary instructions) and **assembly language**, a human-readable symbolic equivalent.

### **3. Memory System and Addressing**  
Explains how each memory cell has a unique **address**. The CPU retrieves data by referencing these address values.  
- **RAM (Random Access Memory):** Volatile memory for read-write operations, typically DRAM or SRAM.  
- **ROM (Read Only Memory):** Non-volatile memory used for permanent data storage.  
- **BIOS:** Firmware that initializes hardware during the boot process and loads the operating system into memory.  

### **4. Cache Memory and Buffer**  
Addresses the performance difference between fast CPUs and slower storage devices.  
- **Cache:** High-speed memory (SRAM) bridging the speed gap between the CPU and main memory.  
- **Buffer:** Temporary storage area facilitating efficient data transfer between devices of differing speeds.

### **5. Secondary and External Memory**  
Discusses mass storage devices such as **hard disk drives (HDDs)** using magnetic platters and **solid-state drives (SSDs)** using flash memory for faster, energy-efficient storage. Also mentions **external drives and USB flash memory** for portable data use.

### **6. Memory Hierarchy**  
Describes the layered structure of memory from fastest to slowest: registers → cache → main memory → secondary storage. Explains cost, capacity, and performance trade-offs that define this hierarchy.

### **7. Central Processing Unit (CPU)**  
Outlines CPU components and their roles:  
- **ALU (Arithmetic Logic Unit):** Executes arithmetic and logical operations.  
- **Control Unit:** Directs processing sequences.  
- **Registers:** Temporarily store operands and results.  
The CPU continuously performs the **fetch–decode–execute cycle**, executing instructions sequentially.

### **8. Program Execution and Machine Cycle**  
Each instruction cycle involves three stages: fetch (retrieve from memory), decode (interpret operation and operands), and execute (perform operation). This cycle repeats continuously to complete program execution.

### **9. Microprocessor and Performance**  
Identifies performance factors such as **bus width**, **clock speed**, **parallel processing**, and **register size**. Describes Intel’s processor evolution (4004 to Pentium, Core i-series) and **Moore’s Law**, predicting that processing power doubles roughly every 18–24 months.  
Compares **CISC (Complex Instruction Set Computing)**, with more complex instruction sets, and **RISC (Reduced Instruction Set Computing)**, focusing on simpler, faster-executing instructions.

</details>


<details>
<summary>KOR (한국어 버전)</summary>

## **4장 – 컴퓨터 구조**  

이 장에서는 컴퓨터의 기본 구조를 다루며, 명령어 실행 과정, 기억장치 구성, 중앙처리장치(CPU)의 역할과 성능 요소를 설명합니다.

### **1. 폰 노이만 구조와 저장 프로그램 개념**  
존 폰 노이만이 제안한 **저장 프로그램 방식**은 프로그램 명령어와 데이터를 같은 기억장치에 저장하는 개념입니다. CPU는 이를 순차적으로 인출(fetch)·해독(decode)·실행(execute)하여 자동화된 연산을 수행합니다.

### **2. 명령어 구성과 저급 언어**  
명령어는 **연산부(opcode)**와 **피연산부(operand)**로 구성되며, 주로 16비트로 표현됩니다. 주요 명령에는 ADD, LOAD, STORE, HALT 등이 있습니다.  
**기계어**는 0과 1의 이진 코드 형태이고, **어셈블리어**는 이를 사람이 인식하기 쉽게 기호로 표현한 언어입니다.

### **3. 기억장치와 주소 체계**  
모든 메모리 저장 위치는 **주소(address)**를 가지며, CPU는 이 주소를 통해 데이터를 접근합니다.  
- **RAM:** 휘발성 메모리로, DRAM과 SRAM이 있으며 주기억장치로 사용됩니다.  
- **ROM:** 데이터를 영구 저장하는 비휘발성 메모리입니다.  
- **BIOS:** 시스템 부팅 시 하드웨어를 점검하고 운영체제를 메모리로 로드하는 펌웨어입니다.

### **4. 캐시 메모리와 버퍼**  
CPU와 메모리 간 속도 차이를 완화하기 위해 **캐시 메모리(SRAM)**를 사용합니다. 캐시는 자주 사용하는 데이터를 일시 저장해 연산 속도를 높입니다. **버퍼**는 입출력 장치 간 속도 차이를 줄이기 위한 임시 저장 공간입니다.

### **5. 보조기억장치**  
주기억장치보다 용량이 크고 비휘발성인 **보조기억장치**는 HDD와 SSD가 대표적입니다.  
- **HDD:** 자기디스크를 이용한 저장 방식.  
- **SSD:** 플래시 메모리 기반으로 속도가 빠르고 소음이 적습니다.  
또한, **외장하드**와 **USB 메모리**는 데이터를 휴대하며 쉽게 전송할 수 있는 기억장치입니다.

### **6. 기억장치 계층 구조**  
기억장치는 속도·용량·가격에 따라 **레지스터 → 캐시 → 주기억장치 → 보조기억장치**의 계층으로 구성됩니다. 빠른 저장장치는 비싸고 용량이 적으며, 느린 저장장치는 저렴하고 용량이 크다는 특성이 있습니다.

### **7. 중앙처리장치 (CPU)**  
CPU는 **연산장치(ALU)**, **제어장치(Control Unit)**, **레지스터(Register)**로 구성됩니다. CPU는 메모리에 저장된 명령어를 인출·해독·실행하여 실제 연산을 수행합니다.

### **8. 명령어 처리 과정과 기계 주기**  
하나의 명령어는 세 단계—인출(fetch), 해독(decode), 실행(execute)—으로 처리됩니다. 이 과정이 반복되어 프로그램이 완전하게 수행됩니다.

### **9. 마이크로프로세서와 성능 요소**  
프로세서 성능은 **자료버스 폭, 클럭 속도, 메모리 크기, 병렬처리, 캐시 용량** 등으로 결정됩니다.  
인텔의 CPU 발전(4004 → 펜티엄 → 코어 i 시리즈)을 통해 프로세서 성능이 상승했으며, **무어의 법칙**은 반도체 집적도가 18~24개월마다 두 배로 증가한다고 설명합니다.  
또한, **CISC**(복합 명령어 집합)과 **RISC**(축소 명령어 집합) 구조의 차이점을 비교하여 컴퓨터 설계 철학의 다양성을 다룹니다.

</details>
