<!-- # A-unique-32-bit-Pipelined-CPU
Designing a 32-bit in-order integer pipelined CPU with data forwarding, an instruction set architecture named NASH, and actively integrated a two-level memory hierarchy model using physical addressing

The CPU functionality will be verified by applying three benchmarks aimed to test different
aspects. The first benchmark is the integer DAXPY with 2-d victors. This benchmark is mainly
aimed to apply a multiply-accumulate operation on two matrices. The second benchmark is the
Merge Sorter plus CRC. This benchmark has two main parts that could be divided into smaller
functions. It is aiming to re-order a given list and appending a CRC code to that list. Our last
benchmark is the Text Parser. This benchmark will investigate a given text and report all types
of spaces in that list, as well as removing any duplicated space. All these benchmarks are going
to be written and assembled using NASH ISA.

In the [Report file](https://github.com/Azizkhaled/A-unique-32-bit-Pipelined-CPU/blob/main/Report%202021%20.pdf), some information on the NASH ISA and the CPU details will be given. Afterward, details on the benchmarks will be displayed. Moreover, testing code details for each benchmark will be shown, along with the results. Finally, Quartus
II verification results will be given. ISA specification and all used codes and test outputs will
be illustrated in the appendix.

### Proposed Datapath
![Datapath](https://github.com/Azizkhaled/A-unique-32-bit-Pipelined-CPU/blob/main/Proposed%20datapath.png)-->


# Unique 32-bit Pipelined CPU

## Project Overview

This repository showcases the development of a 32-bit in-order integer pipelined CPU with data forwarding. The CPU features an instruction set architecture named NASH and includes a two-level memory hierarchy model with physical addressing.

The CPU's functionality is rigorously tested using three benchmarks designed to assess various aspects of its performance:

1. **Integer DAXPY Benchmark:** This benchmark involves multiply-accumulate operations on two matrices using integer calculations.

2. **Merge Sorter plus CRC Benchmark:** Divided into two main parts, this benchmark tests the CPU's ability to reorder a list and append a CRC code.

3. **Text Parser Benchmark:** The CPU processes a given text, identifying different types of spaces and removing duplicates.

All benchmarks are implemented using the NASH instruction set architecture.

## Report and Documentation

For detailed information about the NASH ISA, CPU architecture, and benchmark details, refer to the [Report file](https://github.com/Azizkhaled/A-unique-32-bit-Pipelined-CPU/blob/main/Report%202021%20.pdf). The report covers:

1. NASH ISA and CPU specifications.
2. Detailed benchmark descriptions.
3. Testing code and results.
4. Quartus II verification results.
5. Appendix containing ISA specification, codes, and test outputs.

## Proposed Datapath

View the proposed datapath for the CPU:

![Datapath](https://github.com/Azizkhaled/A-unique-32-bit-Pipelined-CPU/blob/main/Proposed%20datapath.png)

Explore the repository for code, documentation, and insights into this project!

