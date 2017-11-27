GrayLib v1.0, by Runer112 (Zachary Wassall).


== BASICS ==

Welcome to the GrayLib v1.0 readme! GrayLib is an Axe library, designed for Axe 
1.2.1, to provide nearly perfect grayscale and tons of useful related functions 
to Axe programmers with extensive customizability.


== FEATURES ==

 - Tunable crystal timer-based grayscale for non-83+ calculators. Nearly 
     perfect!
 - Tunable slower hardware-timer based grayscale as a fallback for 83+ 
     calculators. Still looks very good!
 - Supports either 3-level or 4-level grayscale.
 - A buffered approach to avoid any frame mixing when rendering new frames.
 - Automatic setting loading and saving from/to an archived variable.
 - Includes a default contrast and grayscale timing tuner which can 
     automatically start on the first run.
 - Masked sprite drawing for both 3- and 4-level grayscale. (Axe's built-in 
     Pt-Mask() command can only draw to a set buffer pair, which is no good 
     for a buffered approach)
 - Text routines to print integers, tokens, strings, and characters in any 
     foreground/background grayscale color combination.
 - Support for hooks in the grayscale update interrupt, which can optionally 
     replace the default grayscale update command.
 - Support for using getKey like normal, despite the OS interrupt not running.


== EXAMPLE PROGRAMS ==

To get a basic idea for how to use GrayLib, I have created a few example 
programs. One is a very basic wrapper for the default tuner, one is a 
screensaver-style bouncing text program, and one is a fairly complicated 
recreation of the movement engine from the first-generation Pokemon games, set 
in Pallet Town. Every example program comes in two forms: a smaller version, 
which contains just the code, and a larger "Commented" version. The commented 
versions contain detailed comments explaining exactly how each piece of the 
code works, and can be good resources for both learning how to use GrayLib and 
simply learning Axe coding approaches and tricks.


== LEARNING TO USE GRAYLIB ==

GrayLib itself also comes in a small version and a commented version. The small 
version is good to store on your calculator if you don't need a reference on 
your calculator about how to use the library. Whether or not you want to store 
the commented version on your calculator, THE COMMENTED VERSION IS CRUCIAL TO 
LEARNING THE MYRIAD OPTIONS AND COMMANDS IN GRAYLIB. This readme will not 
actually explain how to use the library, as it would mostly be redundant with 
the commented version of the library and example programs.


== FEEDBACK ==

If you have any questions, comments, concerns, feature requests, or bug 
reports, the best course of action would be to include them in a post in 
GrayLib's official thread on Omnimaga:

http://www.omnimaga.org/index.php?topic=16901

If posting in the official thread is not a viable option, send me (Runer112) a 
personal message on Omnimaga or send me an email at runer112@gmail.com.