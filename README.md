# Jitsi Phoshell


## Why Phoshell?

As decribed in the following GitHub issue:

- https://github.com/jitsi/jitsi-meet/issues/5269#issuecomment-622661995

  - TLDR: The Tensor Flow (TFJS) Body Pix algorithm is already included in Jitsi-Meet.

As such, we may ask:

- Why hasn't anyone use TFJS Body Pix to extract the human body as avatar, to be used in an Augmented Reality conferencing app?

We suspect there are three primary reasons:

1. The good old learning curve to pick up a new framework / programming language (JavaScript React Redux).

2. Lack of a powerful live debugging system like Forth for new programmers to debug and learn the internal workings of Jitsi.

3. Both reasons above contribute to lack of documentation and manpower to prepare documentation, which lead to a positive feedback in difficulties in getting more developers.

Hence we hope R3ML will overcome these problems, perhaps enable thousands more developers to join our effort &mdash; ___Phoom: an augmented reality conferencing app___. 

The 3 problems mentioned above are not unique to Jitsi. They are perhaps generic to many other free software / open source projects.

- Why do we need that many developers for AR conferencing?

__We believe this is the beginning of a new era of computing:__

- _If the 2010 decade is defined by iPhone and Android mobile devices, then_ ___2020s should be the era of Virtual Reality &mdash; 3D VR AR___, _with opreating systems and devices that transcend the old, but the programming language has to be_ ___powerful___ _like Forth and yet_ ___easy to learn___ _like the Turtle graphics Logo programming language._

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
