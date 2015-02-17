# underload interpreter

This is an interpreter for the esoteric programming language [Underload](http://esolangs.org/wiki/Underload) written in the esoteric programming language [Aheui](http://esolangs.org/wiki/Aheui).
Tested with caheui.

Stack overview
======

The interpreter uses the following Aheui stacks:

* `ㄴ` program code
* `ㄷ` underload stack
* `ㄹ` length of stack elements (a single stack element in underload ca be multiple characters long)
* `ㅁ` temp storage
* `ㄱ` temp storage2
