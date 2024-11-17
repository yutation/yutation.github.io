# Jingtian Dang
I am a 1st-year Ph.D. student at Georgia Tech, advised by  Prof. Tushar Krishna. My research interests are in computer architecture, with a focus on designing efficient and reliable hardware accelerators for specific applications.
![image](./figures/ehad2.jpg)

📧 [dangjingtian@gatech.edu](mailto:dangjingtian@gatech.edu)  
---

## Education

### Georgia Institute of Technology, Atlanta, GA
**Ph.D. in Electrical and Computer Engineering**  
_August 2024 – Present_  
Expected Graduation: 2029  

### Carnegie Mellon University, Pittsburgh, PA
**M.S. in Electrical and Computer Engineering**  
_January 2023 – December 2023_  

### Georgia Institute of Technology, Atlanta, GA
**B.S. in Computer Engineering**  
_January 2021 – December 2022_  
 
### Virginia Tech, Blacksburg, VA
Transfer with 57 Credit Hours  
_August 2019 – December 2020_  

---

## Experience

### Rivos Inc., Mountain View, California  
**Intern Member of Technical Staff in Silicon**  
_May 2023 – August 2023_

---

## Publications

- **ReLU-FHE**: Low-cost Accurate ReLU Polynomial Approximation in Fully Homomorphic Encryption-Based ML Inference  
  _The 3rd On-Device Intelligence Workshop @ MLSys'23_  

- **SmartPAF**: Accurate Low-Degree Polynomial Approximation of Non-Polynomial Operators for Fast Private Inference in Homomorphic Encryption  
  _The Seventh Annual Conference on Machine Learning and Systems (MLSys'24)_

---

## Projects and Research

### Architecture Simulators (February-April 2022)  
**Advanced/high-performance computer architecture course**  
**personal course projects**  
- designed a cache system simulator with L1, L2, and victim cache, a tage branch predictor simulator, a tomasulo simulator, and a mosi cache coherence simulator by c++.  
- found the proper configurations of the simulators for different benchmarks to get high performance.  

### RISC-V 5-stage Pipelined Processor (February-April 2022)  
**Processor design course**  
**team-based projects with 2 members**  
- designed a 5-stage pipelined processor supporting tiny RISC-V by Verilog.  
- optimized the processor with a g-share branch predictor, a branch target buffer, and a return address stack.  
- synthesized the design on Vivado and tested it on pynq-z2 FPGA cloud cluster by Python.  

### SRAM Design (October-December 2022)  
**Advanced VLSI systems course**  
**team-based project with 3 members**  
- designed SRAM array reading and writing peripheral schematic and passed DRC and LVS.  
- solved the problem of the row and column decoder synchronizing with the clock signal.  
- tested the functionality and measured the performance of the SRAM system, which can run at 0.8 v and 1 GHz.  

### Modern Computer Architecture & Design Course Labs (September-October 2023)  
**team-based labs with 2 members**  
- created a bespoke branch predictor (bp) within gem5 by integrating local history bp, tage bp, and perceptron bp.  
- demonstrated a remarkable 1.19x speedup over the baseline across four benchmarks on average, establishing it as the top-performing custom branch predictor in the course.  
- implemented a 4-way issue queue, register renaming, and reorder buffer in Verilog.  

### Reconfigurable Logic: Technology, Architecture, and Applications Course Labs and Projects (October-December 2023)  
**team-based labs or project with 3 members**  
- optimized two convolution layers using HLS and achieved 4.5 gigaop/s, resulting in a 15x speedup compared to the baseline on the FPGA ultra96, ranking third in the course. the exploration involved memory layout, tiling size, and loop order to enhance bandwidth and parallelism.  
- designed an accelerator for the simplex algorithm using HLS on FPGA ultra96, achieving a 150x speedup compared to software. Explored the impact of tiling size and shape on performance and hardware overhead.  

### Digital Systems Testing and Testable Design Course Projects (September-December 2023)  
**team-based labs or project with 2 members**  
- implemented a fault collapser for an SSL ATPG system and a d-algorithm simulator in Python. developed an SSL and bridge fault simulator based on deductive fault simulation algorithms.  
- utilized SSL fault simulator tools to diagnose bridge faults using provided testers, creating a script to automatically generate potential bridge faults in Python.  
- implemented design for testability for isacs89 benchmark sequential circuit s9234 by employing a multiple-channel scan chain, achieving a fault coverage of 93.5% with reasonable time and hardware overhead. the design earned the first-place award judged by Qualcomm.  

---

## Awards

- **Student Travel Grant Award** ($500) | _MLSys Conference, May 2024_  
- **Student Travel Grant Award** ($1000) | _MLSys Conference, May 2023_  
- **ECE Senior Scholar Award** ($500) | _Georgia Tech, April 2023_  
- **Kathy & Joe Timko Scholarship Award** ($2000) | _Virginia Tech, January 2020_

---

## Contact

Feel free to reach out via email, and check out my GitHub portfolio for more details on my projects.

