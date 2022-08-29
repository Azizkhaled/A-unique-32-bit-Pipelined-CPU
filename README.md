# A-unique-32-bit-Pipelined-CPU
Designing a 32-bit in-order integer pipelined CPU with data forwarding, an instruction set architecture named NASH, and actively integrated a two-level memory hierarchy model using physical addressing

The CPU functionality will be verified by applying three benchmarks aimed to test different
aspects. The first benchmark is the integer DAXPY with 2-d victors. This benchmark is mainly
aimed to apply a multiply-accumulate operation on two matrices. The second benchmark is the
Merge Sorter plus CRC. This benchmark has two main parts that could be divided into smaller
functions. It is aiming to re-order a given list and appending a CRC code to that list. Our last
benchmark is the Text Parser. This benchmark will investigate a given text and report all types
of spaces in that list, as well as removing any duplicated space. All these benchmarks are going
to be written and assembled using NASH ISA.

In the Report file, some information on the NASH ISA and the CPU details will be given. Afterward, details on the benchmarks will be displayed. Moreover,
testing code details for each benchmark will be shown, along with the results. Finally, Quartus
II verification results will be given. ISA specification and all used codes and test outputs will
be illustrated in the appendix.
