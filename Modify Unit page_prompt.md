## # Prompt for Gemini – Modify `/Units` Page (keep existing design, add unit resource buttons)

Modify the existing `/Units` page of my web app. **Important:** Keep the current design, colors, typography, layout, and styling exactly as they are. Do not add new CSS, margins, shadows, or colors unless they already exist. Do not change anything visual except adding the functionality described below.

## 1. Add two selectors (two-step)

-   **First selector (Level):** options `IGCSE` and `A Level`
    
-   **Second selector (Exam Board):** depends on chosen level
    
    -   If Level = `IGCSE` → options `CAIE` and `Edexcel`
    -   If Level = `A Level` → options `CAIE` and `Edexcel (IAL)` When the user selects a level and an exam board, display the corresponding units below.
-   Each unit must show:
    
    -   **Topic number**
        
    -   **Topic name**
        
    -   **Mini description** (short, one or two lines)
        
    -   **A button** that says "Access Resources".
        

### 2. Contents of the units

#### CAIE + IGCSE

[Topic 1 – Number Systems]  
Mini description: [How data is stored in binary, hexadecimal, two's complement, binary arithmetic, binary shifts, data storage measurement]

[Topic 2 – Data Representation]  
Mini description: [Character sets (ASCII, Unicode), Bitmap images, Sound, Lossless and Lossy Compression]

[Topic 3 - Databases]
Mini description: [Data types, Database fundamentals (fields, records, primary key, validation), SQL queries]

[Topic 4 - Logic Circuits]
Mini description: [Logic gates, Logic circuits, Trace tables, Problem statements]

[Topic 5 - Computer Architecture]
Mini description: [Von Neumann Architecture, Components of the computer, Components of the CPU, Fetch-Decode-Execute Cycle, Factors that affect the performance of a CPU (core, cache size, clock speed), Instruction set, Embedded Systems]

[Topic 6 - Software and Operating Systems]
Mini description: [Types of software (Application and System software), Functions of the OS, Firmware & BIOS, Interrupt Handling]

[Topic 7 - Programming Languages & Translators]
Mini description: [High-level, low level and assembly languages, Translators (Compilers, Interpreters), Role of the IDE in writing programs]

[Topic 8 - Algorithm Design]
Mini description: [Program Development Life Cycle, Subsystems, Structured Diagrams, Flowcharts, Trace tables]

[Topic 9 - Programming with Pseudocode]
Mini description: [Variables, Constants, Operators, Programming Constructs (Sequence, Selection, Iteration), Standard Methods of Solution, String Handling, Built-in Functions, Variable scope, 1D and 2D arrays]

[Topic 10 - Hardware: Memory & Storage]
Mini description: [Input and Output Devices, Memory (RAM, ROM), Storage (Magnetic, Optical, Solid-state, Virtual memory]

[Topic 11 - Automated and Emerging Technologies]
Mini description: [Automated Systems, Robotics, Artificial Intelligence]

[Topic 12 - Further Programming]
Mini description: [Searching and Sorting Algorithms, validation checks, test data, Subprograms (Functions and Procedures), Variable scope, File Handling]

[Topic 13 - Data Transmission]
Mini description: [Methods: Serial, Parallel, Simplex, Half-duplex, Full duplex, Methods of error detection: Parity Bit, Parity Block Check, Checksum, Echo Check, Check Digit, Automatic Repeat Query (ARQ), Encryption]

[Topic 14 - Networks & The Internet]
Mini description: [Network Hardware (NIC, MAC, IP, router), The Internet, URL, HTTP, web browser, HTML, DNS, cookies, Digital Currency (Blockchain)]

[Topic 15 - Cybersecurity]
Mini description: [Cybersecurity threats, Solutions to these security threats]

#### EDEXCEL + IGCSE
[Topic 1 - Data Representation I. Number Systems]
Mini description: [Use of Binary, Binary and Hexadecimal Number Systems, Conversions between systems, Binary Arithmetic]

[Topic 2 - Data Representation II. Text and Multimedia]
Mini description: [Text Representation, Bitmap Images, Sound Representation, Limitations on Binary Representation]

[Topic 3 - Data Representation III. Storage, Compression ( Encryption]
Mini description: [Data Storage, File Size Expressions, Data Compression: Lossless and Lossy, Data Encryption]

[Topic 4 - Hardware I. Structure of Machines]
Mini description: [Machines and Computational Modelling, Logic: the Foundation of Hardware, Hardware Components of a Computer System, Memory, Von Neumann Model, Factors that affect the performance of the CPU]

[Topic 5 - Hardware II. Secondary Storage on Devices]
Mini description: [Storing Data on Physical Devices, Embedded Systems]

[Topic 6 - Software I. Operating Systems]
Mini description: [Types of Software, Simulating and Modeling Real World, Functions of an OS, Utility Software]

[Topic 7 - Software II. Languages and Translators]
Mini description: [Languages: LL and HL, Translators: Interpreters and Compilers]

[Topic 8 - Computational Thinking]
Mini description: [Decomposition and Abstraction, Algorithms, Searching and Sorting Algorithms]

[Topic 9 - Programming I]
Mini description: [Data Types, Variables and Constants, Input and Output, Operators, Programming Constructs, Data Structures]

[Topic 10 - Programming II]
Mini description: [Validation of Data Input, Subprograms, File Handling]

[Topic 11 - Networks]
Mini description: [Network Design & Protocols, The Internet & The World Wide Web]

[Topic 12 - Network Security]
Mini description: [Security Fundamentals, Cyber threats and Attacks, Vulnerability Assessment, Protection of Mitigation Strategies]

[Topic 13 - The Bigger Picture]
Mini description: [Environmental Impact, Ethical Impact, Legal Impact, Emerging Technologies]

#### CAIE - AS 
[Topic 1 - Algorithm Design and Problem Solving]
Mini description: [Computational Thinking Skills, Algorithms, Flowchart]

## 3. Initial state

Before any selection, show a message like: *"Select your level and exam board to see units and resources."*

## 4. Button behaviour

-   Each unit card must have a button (e.g., "Access Resources").
-   The button should link to a separate page for that unit's resources. For now, use a relative path such as `/resources/level/option/unit <topic number>. <topic name>` . Also, create the empty page with the same style of the website.
-   Style the button to match your existing design (if you have button styles, reuse them; otherwise, a simple blue background or outline is fine).

Now, generate the complete code for the `/Units` page based on the real data I will fill in the placeholders above. [I have placed only the contents of CAIE-IGCSE as a proof. If this is working I will update this prompt with all the unit contents of all the exam boards/levels]
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTMzNjA4NzU3MCw4Nzk5MTgyOCwtMTg0Nj
c0MDk4NywtMTY4MjU1OTQ0M119
-->