# Jingtian Dang

📧 [dangjingtian@gmail.com](mailto:dangjingtian@gmail.com)  
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

### architecture simulators (february-april 2022)  
**advanced/high performance computer architecture course**  
**personal course projects**  
- designed a cache system simulator with L1, L2, and victim cache, a tage branch predictor simulator, a tomasulo simulator, and a mosi cache coherence simulator by c++.  
- found the proper configurations of the simulators for different benchmarks to get high performance.  

### risc-v 5-stage pipelined processor (february-april 2022)  
**processor design course**  
**team-based projects with 2 members**  
- designed a 5-stage pipelined processor supporting tiny risc-v by verilog.  
- optimized the processor with a g-share branch predictor, a branch target buffer, and a return address stack.  
- synthesized the design on vivado and tested on pynq-z2 fpga cloud cluster by python.  

### sram design (october-december 2022)  
**advanced vlsi systems course**  
**team-based project with 3 members**  
- designed sram array reading and writing peripheral schematic and passed drc and lvs.  
- solved the problem of the row and column decoder synchronizing with clock signal.  
- tested the functionality and measured the performance of the sram system, which can run in 0.8 v and 1 ghz.  

### modern computer architecture & design course labs (september-october 2023)  
**team-based labs with 2 members**  
- created a bespoke branch predictor (bp) within gem5 by integrating local history bp, tage bp, and perceptron bp.  
- demonstrated a remarkable 1.19x speedup over the baseline across four benchmarks on average, establishing it as the top-performing custom branch predictor in the course.  
- implemented a 4-way issue queue, register renaming, and reorder buffer in verilog.  

### reconfigurable logic: technology, architecture, and applications course labs and projects (october-december 2023)  
**team-based labs or project with 3 members**  
- optimized two convolution layers using hls and achieved 4.5 gigaop/s, resulting in a 15x speedup compared to the baseline on the fpga ultra96, ranking third in the course. the exploration involved memory layout, tiling size, and loop order to enhance bandwidth and parallelism.  
- designed an accelerator for the simplex algorithm using hls on fpga ultra96, achieving a 150x speedup compared to software. explored the impact of tiling size and shape on performance and hardware overhead.  

### digital systems testing and testable design course projects (september-december 2023)  
**team-based labs or project with 2 members**  
- implemented a fault collapser for an ssl atpg system and a d-algorithm simulator in python. developed an ssl and bridge fault simulator based on deductive fault simulation algorithms.  
- utilized ssl fault simulator tools to diagnose bridge faults using provided testers, creating a script to automatically generate potential bridge faults in python.  
- implemented design for testability for isacs89 benchmark sequential circuit s9234 by employing a multiple-channel scan chain, achieving a fault coverage of 93.5% with reasonable time and hardware overhead. the design earned the first-place award judged by qualcomm.  

### fully homomorphic encryption (fhe) hardware accelerator (january 2022 - present)  
**major researcher**  
- built the bfv scheme in the fhe library with support for encryption, decryption, addition, multiplication, and relinearization, utilizing residue number system and number theoretic transform optimizations in c++.  
- acquired comprehension of bgv, bfv, and ckks schemes alongside their base ring learning with errors (rlwe) cryptographic algorithms.  
- conducted performance measurements and comparisons of the current he software library, such as microsoft seal and openfhe.  
- developed a simulator to evaluate the performance and memory overhead of various ring-based polynomial algorithms. implemented schoolbook, ntt, and karatsuba ring-based polynomial multiplication using sycl hls, assessing their latency and overhead through synthesis results.  
---

## Awards

- **Student Travel Grant Award** ($500) | _MLSys Conference, May 2024_  
- **Student Travel Grant Award** ($1000) | _MLSys Conference, May 2023_  
- **ECE Senior Scholar Award** ($500) | _Georgia Tech, April 2023_  
- **Kathy & Joe Timko Scholarship Award** ($2000) | _Virginia Tech, January 2020_

---

## Contact

Feel free to reach out via email or phone, and check out my GitHub portfolio for more details on my projects.

