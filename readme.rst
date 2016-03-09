=====
LOLAN
=====

:Author: Richard Brooksby
:Date: 2016-03-07

LOLAN is a compiler for a Forth-like language for the Amstrad CPC
microcomputer.

I wrote it when I was 16.  At that time I had never really seen a
compiler or any programming languages except BASIC and assembler.  I was
fascinated by the Jupiter ACE microcomputer, which had FORTH instead of
BASIC, and somehow got hold of the book "FORTH on the BBC Microcomputer"
by Richard de Grandis-Harrison.  I stared at that book for a long time
and deduced how to make a compiler for FORTH without any real knowledge
of compilers.

LOLAN is not a traditional threaded-interpretive FORTH, but compiles
straight to Z80 opcodes.  Most words are compiled straight to CALL
instructions.

The computer was written using the GEN80 assembler, and the source code
is in a binary format.  I am working on decoding it.

Everything still runs in a CPC464 emulator.  You can load the
"lolan.dsk" and enter::

    RUN"LOLANC.BIN

to start the compiler.  Try::

    0 load> pede.0

to load the "Pede" game, then::

    game

to start it.  It was programmed for the Amstrad joystick, and you may
find it impossible to control.

There's also a Tron lightbikes game, referring to the 1982 movie "Tron".

I made various low-level utilities in LOLAN.

There was a successor, LOLAN 2, which I'll also work on retrieving from the archives.
