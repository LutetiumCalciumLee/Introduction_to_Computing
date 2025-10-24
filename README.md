<details>
<summary>ENG (English Version)</summary>

## **Chapter 4 – Computer Architecture**  

This chapter provides an overview of computer architecture, explaining how computers process and execute instructions, manage memory, and organize internal components such as the CPU, buses, and storage hierarchy.

### **1. Von Neumann Architecture and Stored Program Concept**  
Introduces the stored-program concept proposed by John von Neumann, where both data and instructions are stored in the same memory. The CPU sequentially fetches, decodes, and executes these instructions, enabling programmable and automated computing.

### **2. Instruction Structure and Machine Languages**  
Describes the format of an instruction: operation part (opcode) and operand part (address). Instructions are often 16 bits, divided into 4-bit operation codes and 12-bit address fields. Basic operations include ADD, LOAD, STORE, and HALT. Also explains machine language (binary instructions) and assembly language, a human-readable symbolic equivalent.

### **3. Memory System and Addressing**  
Explains how each memory cell has a unique address. The CPU retrieves data by referencing these address values.  
- **RAM (Random Access Memory):** Volatile memory for read-write operations, typically DRAM or SRAM.  
- **ROM (Read Only Memory):** Non-volatile memory used for permanent data storage.  
- **BIOS:** Firmware that initializes hardware during the boot process and loads the operating system into memory.

### **4. Cache Memory and Buffer**  
Addresses the performance difference between fast CPUs and slower storage devices.  
- **Cache:** High-speed memory (SRAM) bridging the speed gap between the CPU and main memory.  
- **Buffer:** Temporary storage area facilitating efficient data transfer between devices of differing speeds.

### **5. Secondary and External Memory**  
Discusses mass storage devices such as hard disk drives (HDDs) using magnetic platters and solid-state drives (SSDs) using flash memory for faster, energy-efficient storage. Also mentions external drives and USB flash memory for portable data use.

### **6. Memory Hierarchy**  
Describes the layered structure of memory from fastest to slowest: registers → cache → main memory → secondary storage. Explains cost, capacity, and performance trade-offs that define this hierarchy.

### **7. Central Processing Unit (CPU)**  
Outlines CPU components and their roles:  
- **ALU (Arithmetic Logic Unit):** Executes arithmetic and logical operations.  
- **Control Unit:** Directs processing sequences.  
- **Registers:** Temporarily store operands and results.  
The CPU continuously performs the fetch–decode–execute cycle, executing instructions sequentially.

### **8. Program Execution and Machine Cycle**  
Each instruction cycle involves three stages: fetch (retrieve from memory), decode (interpret operation and operands), and execute (perform operation). This cycle repeats continuously to complete program execution.

### **9. Microprocessor and Performance**  
Identifies performance factors such as bus width, clock speed, parallel processing, and register size. Describes Intel’s processor evolution (4004 to Pentium, Core i-series) and Moore’s Law, predicting that processing power doubles roughly every 18–24 months.  
Compares CISC (Complex Instruction Set Computing), with more complex instruction sets, and RISC (Reduced Instruction Set Computing), focusing on simpler, faster-executing instructions.

</details>

<details>
<summary>KOR (한국어 버전)</summary>

## **4장 – 컴퓨터 구조**  

이 장은 컴퓨터의 기본 구조, 명령어 실행 과정, 기억장치 구성, 중앙처리장치(CPU)의 역할과 성능 요소에 대한 설명임.

### **1. 폰 노이만 구조와 저장 프로그램 개념**  
존 폰 노이만이 제안한 저장 프로그램 방식은 프로그램 명령어와 데이터를 같은 기억장치에 저장하는 구조임. CPU는 이것을 순차적으로 인출, 해독, 실행하여 자동화된 연산을 수행함.

### **2. 명령어 구성과 저급 언어**  
명령어는 연산부(Opcode)와 피연산부(Operand)로 구성됨. 대부분 16비트로 표현되며, 주요 명령어로는 ADD, LOAD, STORE, HALT가 있음. 기계어는 이진 코드 형태임, 어셈블리어는 사람이 읽기 쉬운 기호로 표현된 언어임.

### **3. 기억장치와 주소 체계**  
모든 메모리 저장 위치는 고유한 주소(Address)를 가짐. CPU가 주소를 참조하여 데이터를 접근함.  
- RAM: 휘발성 메모리로, 읽기-쓰기 작업에 사용됨.  
- ROM: 비휘발성 메모리로, 영구 데이터 저장용임.  
- BIOS: 하드웨어 초기화 및 운영체제 메모리 로드를 담당함.

### **4. 캐시 메모리와 버퍼**  
캐시 메모리(SRAM)는 CPU와 메모리 간 속도 차이를 완화하는 역할임. 버퍼는 서로 다른 속도의 장치 간 효율적 데이터 전달을 위해 임시로 데이터 저장을 수행함.

### **5. 보조기억장치**  
HDD와 SSD는 대용량 데이터를 저장하는 보조기억장치임. 외장하드와 USB 메모리는 휴대성과 데이터 전송의 용이성을 제공함.

### **6. 기억장치 계층 구조**  
기억장치는 레지스터 → 캐시 → 주기억장치 → 보조기억장치의 계층 구조로 속도, 용량, 가격에 따라 구분됨.

### **7. 중앙처리장치 (CPU)**  
CPU는 연산장치(ALU), 제어장치(Control Unit), 레지스터(Register)로 구성됨. 명령어 인출, 해독, 실행의 연산 사이클을 반복함.

### **8. 명령어 처리 과정과 기계 주기**  
명령어는 인출, 해독, 실행의 세 단계로 처리됨. 프로그램 완수까지 해당 사이클이 반복됨.

### **9. 마이크로프로세서와 성능 요소**  
프로세서 성능은 버스 폭, 클럭 속도, 병렬처리, 레지스터 크기 등에 의해 결정됨. 인텔 CPU의 발전과 무어의 법칙을 통해 성능 증가 양상을 설명함. CISC와 RISC 구조의 차이는 명령어 집합의 복잡성에 있음.

</details>
