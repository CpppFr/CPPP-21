# Exceptional C++

# Victor Ciura

When writing code we usually focus our attention on the happy paths - that’s where the interesting stuff happens. But there are also plenty of exciting things happening on the error handling flow, too. Although not universally loved/used, exceptions are a powerful mechanism of maneuvering execution on the unhappy path. Even if std::exception and related machinery are not your cup of tea, you might care about hardware faults or OS signals like access violations, page errors, ALU overflows. Let’s take a deep dive and explore what happens when an exception occurs, both at the application level and the OS level. We’ll explore the unwind process, the compiler generated code, the CRT hooks available and other exception internals. As we’re taking the scenic Windows route, we’re also going to encounter async exceptions (structured exceptions) on our quest for a better crash. We’ll poke into these mechanisms and see how we can leverage them in our application error handling. Did I mention threads? Routing exceptions between threads… oh my!

## Slides

[Exceptional C++ - Victor Ciura](slides.pdf)