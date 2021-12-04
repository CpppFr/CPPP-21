# A Series of Unfortunate Bugs

# Satabdi Das

Any C++ developer working in a large codebase is very likely to experience weird bugs. In this talk, I'll be sharing with you post-mortem of a set of weird bugs that occurred in deceptively simple code but were difficult to debug. Many of these bugs occurred at unfortunate moments - for instance, just before the day of the release or at the customer site. Almost all of them took nontrivial amount of time to debug them. But surprisingly it took only a few lines of code to fix them. The cause of these bugs range from static buffer overflow and stack corruption to undefined behaviours and many other exciting ways to break a C++ program. In this talk I’ll present the code snippets in which the bugs occurred, show you the fixes and share with you the pitfalls to avoid these bugs. Through these bugs, we focus on how to get better at debugging.

## Slides

[A Series of Unfortunate Bugs - Satabdi Das](slides.pdf)