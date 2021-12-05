# SIMD in C++20 - EVE of a new Era

# Joël Falcou

<p>In those days and ages of GPGPU, Cloud Computing, and other bleeding-edge large-scale computing architectures, peoples often forget that 150% of their CPU comes with a layer of Instruction Level Parallelism: their SIMD computing unit.  If writing code using SIMD systems was less of a nightmare then, yeah, people would use it. So, obviously, we had to write a library for it.</p><p>Writing SIMD wrapper libraries is not a new idea and a bunch exists already. What we want to showcase here is EVE :  a C++20 library giving access in a uniform way across both ARM (neon) and x86 (from sse2 to avx-512).. </p><p>Its main advantages over similar libraries include:</p><ul><li>STL like algorithm support, including zip to operate on multiple ranges.</li><li>ARM support (many libraries only support x86)</li><li>A very comprehensive math library.It is liberally licensed and intended to be production quality.</li></ul><p>This talk will include a collection of demos (like <a href="https://godbolt.org/z/n6Pds78s6">https://godbolt.org/z/n6Pds78s6</a>) for different library features and benchmarks, as well as practical advice on using EVE in your projects.</p>

## Slides

https://denisyaroshevskiy.github.io/eve_2021_presentation/

## Backup PDF export

[SIMD in C++20 - EVE of a new Era - Joël Falcou](export.pdf)
