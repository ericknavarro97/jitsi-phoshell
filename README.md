# Jitsi Phoshell

Phoshell is derived from the Forth programming language, as we took critical features from Forth and simplify them, to create a highly portable stack machine shell that can be implemented in around 50 lines of JavaScript code or equivalent, that essentially does the following:
- pushes non-function words (tokens) on to the stack;
- executes function words and pushes the results on to the stack.

Phoshell was initially implemented in PHP as an experiment to see how easy it is to implement a simplified stack machine. Eventually, we realized that this simplified stack machine can in fact be implemented in ___any known programming language___ _with the equivalent of around 50 lines of JavaScript or PHP code_, thus making the Forth like script (hence _"Phos"_) a likely candidate to be a ___universal scripting language___.

Besides Forth implementations in other programming languages (from C/C++ to Lisp, JavaScript, Java, Rust, Haskell etc.) developed by other programmers, which we too classify as "stack machine shells" (smashlet), we ourselves have implemented Phoshell in:

- C, C++, PHP, Python, Java, JavaScript &mdash; on desktop Linux and Android (Java and NDK)
- Using Laravel Blade PHP, we succeeded in creating a Reverse Polish form of HTML!! &mdash; _a breakthrough perhaps as significant as the invention of HTML itself??_
- An attempt to implement raw Forth within Firefox JavaScript engine as a ___compatible___ alternative to WebAssembly


<img src="https://github.com/udexon/Phoom/blob/master/jitsi_phoshell/jm_chat_icon.png" width=600>

<img src="https://github.com/udexon/Phoom/blob/master/jitsi_phoshell/jm_phoshell.png" width=600>
