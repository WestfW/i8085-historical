# i8085-historical
8085 tools for TOPS10.

In 1979, I took CIS580B "Intro to Microprocessors" at the University of Pennsylvania.  The 5xx-series classes were essentially "topics too new to be in the undergrad cirricula, and too basic to be part of the graduate cirricula, so they're open to all as electives."  Microprocessors were pretty new at the time.

The class covered mostly the 6800.  It required a final project, and I chose to imlpement a simulator for the 8085 CPU that was also current at the time.

This was written in PDP10 assembly lanaguage (Macro-10), designed to run on Wharton-10, where I had managed to wrangle a job as "computer operator"  (memorable interview exchange: "So basically you want to play on our computer, and are willing to work to get access?"  "Well, yes.")

Of course, I had to write an assembler that ran on the 10 as well.  That was relatively easy to implement as macros within Macro-10, incidentally giving one acess to the advanced capabilities of that assembler "for free."

And some sample code.

So the pieces were:

m8085.mac: the simulator.  All I seem to have left is a printout, and a 9-track tape (essentially unreadable :-( )

8080a.mac: the assembler.  Found it in my file archives!

forth.m85: an implementation of Forth, from Kilobaud magazine

ddt.m85: a monitor debugger for 8085.  this came later, and I don't think I ever actually ran it.  (At some point, I bought a Godbout 8085/8086 dual CPU board with the idea that I'd put together a CP/M system, but I got sidetracked by "real work" on TOPS20 mainframes.)

(While the "copyright" noticed in 8085a.mac says 1981, that was added after I learned more about copyrighting my work!)

Incidentally, the simulator was "published" on the ARPANet - accessible via anonymous FTP and mentioned on some of the mailing lists that existed at the time.  A few years later, now a "professional" TOPS20 "System Programmer", I attended a DECUS symposium where one of the talks was about a simulator that ran on PDP10s, and allowed mainframe users to run popular CP/M programs.  I asked questions and mentioned that I had written something similar in college...  Afterward, the presenter came up to me and said something along the lines of: "um.  We sort-of started with your code, that we found on the Internet, and we'd like to give you a free copy of our product..." (To be fair, there's a large gap between what I did and a useful CP/M emulator, so I didn't at all feel "ripped off."  Also, that was about the same timeframe that the IBM PC came out, and CP/M's days were numbered.)

