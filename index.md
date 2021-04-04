This project have as objective allow to share and publish live atari 8-bit content to the web.

## Atari BASIC

- [Atari Basic Online](https://eahumada.github.io/AtariOnline/basic/basic-mame.html?)
- [Goblin Online](https://eahumada.github.io/AtariOnline/basic/goblin-mame.html?)

## Atari Logo

- [Logo English](https://eahumada.github.io/AtariOnline/logo/logoeng-mame.html)
- [Logo Spanish](https://eahumada.github.io/AtariOnline/logo/logospa-mame.html)

## [Live tutorials from Atari Projects](http://atariprojects.org/)

Fun projects for your Atari 8-bit home computers and video game consoles, you can read the articles [here](http://atariprojects.org/)

- Screen Flipping ( [jsA8E](https://eahumada.github.io/AtariOnline/atariprojects.html?disk_filename=flip.atr) ) ([MAME](https://eahumada.github.io/AtariOnline/atariprojects/basic-mame.html)) Type: RUN "D:FLIP.BAS" [Return]
- Horizontal Scrolling ( [jsA8E](https://eahumada.github.io/AtariOnline/atariprojects.html?disk_filename=scrolling.atr) ) ( [MAME](https://eahumada.github.io/AtariOnline/atariprojects/basic-mame.html) ) Type: RUN "D:HSCROLL.BAS [Return]

## Atari Assembler Editor

Based on the great videos from [8-bit and more](https://www.youtube.com/watch?v=gOIa6_2_sxw), here is a live environment to practice the coding tutorials.

[Live Atari Assembler Editor](https://eahumada.github.io/AtariOnline/assembler/assembler-mame.html) ( [jsA8E](https://eahumada.github.io/AtariOnline/assembler.html?disk_filename=atariassembler.atr) )
( [MAME](https://eahumada.github.io/AtariOnline/assembler.assembler-mame.html) )

Simple loop:
```
ENTER #D:ATASM01.ASM [Return]
ASM [Return]
BUG [Return]
S1000 [Return]
S [Return]
```
(repeat S until you reach the BRK)

Sprite:
```
ENTER #D:SPRITE1.LST
ASM
BUG
G500B
```

## MAC/65 Assembler Editor With DDT

[Live MAC/65 with DDT](https://eahumada.github.io/AtariOnline/mac65/mac65-mame.html) [MAME](https://eahumada.github.io/AtariOnline/mac65/mac65-mame.html) 

## FastBasic Demos

[Live FastBasic Demos](https://eahumada.github.io/AtariOnline/fastbasic/fastbasic-mame.html) 

- Type: PMTEST.COM
- Type: JOYAS.COM

```
To list all demos:
DIR *.COM [Return]
```

## B2FJ Virtual Machine

B2FJ is a Virtual Machine intended to run Java bytecode on the 8-bit home computers of the 80s.

Here is the port to Atari playing music and using PM graphics for the dancing bar.

This port is capable of multihreading and automatic Garbagge Collection.

More Info on this [link](https://mzattera.github.io/b2fJ/)

[B2FJ Demo](http://localhost:8002/demos/demos-mame.html?disk=b2fj.atr)

