# Correctly Calculating `min`, `max`, and More

# Walter E Brown

The C++ standard library long ago selected `operator ＜` as its ordering primitive, and even spells it in several different ways (e.g., `std::less`). This talk will explain why `operator ＜` (and its aliases) must be used with care, in even such seemingly simple algorithms as `max` and `min`.

We will also discuss the use of `operator ＜` in several other order-related algorithms, showing how easy it is to make mistakes when using the `operator ＜` primitive directly, no matter how it’s spelled.

(Of course, we will also present a straightforward technique to avoid such mistakes.)

## Slides

[Correctly Calculating `min`, `max`, and More - Walter E Brown](slides.pdf)