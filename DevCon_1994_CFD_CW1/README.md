#  DevCon 1994 

### September 1994 – Boca Raton – The Boca Raton Beach Club and Resort

The hotel was a pretty snazzy resort. We had a big name keynote of columnist John Dvorak from PC Magazine. The major topics at this DevCon were the updated DOS product CFD 3.1 (that was nearing completion) and the Windows product initially called Clarion Database Developer for Windows 1.0. The name was a mouthful so CDDW 1.0 eventually was called CW 1.0. 

CDDW had not shipped gold yet, the price list shows it as a Beta as do my notes. Microsoft Windows was version 3.1, aka Windows for Workgroups, and 16-bit. Windows NT 3.5 "Daytona" had been shipped in September of 1994 by Microsoft as the first 32-bit Windows. Windows 95 did not ship until a year later in August 1995. 

We all had a CDDW training session in a little computer lab lead by Richard Taylor where we were able to use CW for the first time. I recall it as being fantastic. It was "Clarion Easy" to design a working Window program. Cool! . At the PC next to me was Stamos. There was no Report template so you hand coded it.

I do not have the brochure, so if you have it please contract me. I scanned the Schedule to a PDF to give you an idea of the topics. I scanned a few session papers. All of the best sessions, e.g. showing the new products, had no slides in the book.  I typed a few of my notes below. If you have more to add please post it on Clarion Hub.

## Clarion Language Enhancements - David Bayliss

* New UnTyped Parameter Type ? for passing by Value
* New UnTyped Parameter Type *? for passing by Address
* GROUP can have TYPE and BINDABLE.  Named Group Parameters.
* EVALUATE() function

## Getting the Most Out of Clarion  - David Bayliss

This session was called an update to the 1993 "Squeezing the Last Drop" session. David said it was not a question of whether a Clarion programmer could take on a C Programmer, but could he take on a TEAM of C programmers. I have some notes but trying to turn them into something meaningful is too hard. They are 18 years old so probably best to read the current docs.

One tip I’ll pass on is that the CASE statement is highly optimized for LONG, SHORT and STRING(1). I have found this myself in some testing.
ROUTINEs were made faster via the way DO and EXIT work, they are a simple jump. Routine local DATA takes an extra 3 bytes. Implicit variables in a Routine are a bad choice. RETURN from a Routine takes 40 bytes extra. Routines get a round ISL limits so are a good way to break up large embeds. (Carl Note: Classes did not exist in Cw 1 and are an alternative)

## Q&A Session – Bruce Barrington

Always a highlight the final session was hearing the boss reveal some inside info about things that had happened we did not know about, and what was planned for the future. I took a few notes that I put below. I would also point out that the price sheet (in the schedule PDF) shows that CDD 3.0 was for sale, so no CFD 3.1 yet, and Clarion for Windows was sold as a Beta. The Bob Butler PDF shows he had a Windows version of Time Matters so he had used the Beta.

* No firm date on CDDW Gold shipping. They were not going to add any more functionality, just fix the bugs and make one more Beta release. My 1.003 is dated 6-7-1995.
* CFD 3.1 was in initial Beta with some customers. Did not have ship date.
* Working on 32-bit DOS compilers. Also Jensen C, C++ and Modula-2 compilers as part of the CFD IDE.
* Clarion Chicago Compiler and Linker. The Microsoft "Chicago" project turned into Windows 95 their first 32-bit Consumer OS. Betas came out in 1993-1994 so the Dev Center had one.
* Next release of CW could be 32-bit. I took this to mean a 32-bit IDE and possibly TS thought it would be possible. Version 1.5 did offer 32-bit compilers but the IDE remained 16-bit until replaced by SharpDevelop in 7.0.
* Future Project - Report Writer for Windows
* Future Project - Personal Developer for Windows (never happned)
* Future Project - TopSpeed Data Base driver – BB said "Very promising" and it did prove amazing. - CW 1.003 has a TPS driver.

