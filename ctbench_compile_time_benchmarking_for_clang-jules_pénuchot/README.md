# ctbench: compile time benchmarking for Clang

# Jules Pénuchot

<p>As C++ metaprogramming paradigm grows richer revision after revision, C++ metaprograms get more complex, more powerful, and therefore compile times increase over time. Common knowledge about the impact of metaprogramming mechanisms like SFINAE, concepts, or <code>if constexpr</code> on compile times are now parts of the C++ culture, but actual analysis of their behavior remains few and far between.</p><p>Compile time analysis should become as trivial as runtime analysis.</p><p><code>ctbench</code> was made with that purpose in mind and proposes a way of gathering, analysing, and comparing granular compile time data using Clang's time-trace feature. It provides a C++/CMake developer-friendly API to declare parametric compile-time benchmarks and comparisons through flexible plotting backends.</p>

## Slides

https://jpenuchot.github.io/slides/jpenuchot-cppp-21-ctbench.pdf

## Project

https://github.com/JPenuchot/ctbench

## Backup PDF export

[ctbench: compile time benchmarking for Clang - Jules Pénuchot] (export.pdf)