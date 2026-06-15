# PICORV23 Cache Controller

A Verilog implementation of a direct-mapped cache controller designed for the PicoRV32 RISC-V processor.
The cache sits between the PicoRV32 processor and main memory, serving frequently accessed data directly from the cache when available and fetching data from memory on cache misses via an AXILITE interface.
Cache files are located in cache_pico/cache_pico.srcs/sources_1/imports/cs391r1-lab6/cache.sv

## Tech Stack
- Verilog
- AXI Protocol
- FPGA Development Tools

## Attributions

This was our final capstone for BUCS391r1. The contributors for this project were:
- Isaac Meza
- Ruby Chen
- Beren Akpinar
- Michael Ross
