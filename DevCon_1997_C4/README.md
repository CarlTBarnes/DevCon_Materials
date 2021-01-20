#  DevCon 1997

### September 22-24, 1997 – Fort Lauderdale – Radisson Bahia Mar Double Tree

These are my recollections, I could be wrong. Please contribute comments and corrections on the ClarionHub thread and I'll post here.

This DevCon was about Clarion 4 and the first time seeing the OOP ABC Templates to replace what are now called the Legacy Clarion templates. The results ABC of turning things like a Browse into an Object have proven brilliant.

I am having some trouble recalling this DevCon. I can picture the hotel and my notes make sense, but its a bit hazy. It appears this show was about CW 2.0 which was around 2.003. There is a nice CW2 brochure (Mark_Cw2_Flyer.PDF) in the Marketing folder. Clarion 4 with ABC OOP was shown and discussed. Possibly CWIC was a major topic.

The fun event was Mardi Gras Night where Clarion developer Andrew Guidroz cooked Cajun for us. IIRC it was Shrimp Etouffee over Fried Catfish. Yum! There was to be a Cajun tradition of white cake with a Plastic Baby prize baked inside. Whomever found the baby got some kind of prize. The hotel kitchen thought that could be a choking hazard so the Plastic Baby was tapped under a chair. I don't recall who won or the prize. I do recall Sabrina Guidroz saying something about her having baby inside so she should get the prize. Andrew promised her a prize later.

Many of the best session did not come with slides so below I'll type a few notes...

## Clarion's Bright Future - Bruce Barrington

This was the first morning after the keynote. BB talked about "Reinventing Clarion" with new marketing, new product names, new graphics, new logos, advertising, tradeshows, roadshows. In the Marketing folder I have some materials like "Why Clarion". I recorded these notes:

* Templates provide code you'd be proud to write but are darn happy you did not have to
* Enterprise Edition coming in by January 1998 with Data Modeler, Deployment (the install builder), Version Control, SQL Drivers
* TopSpeed driver toolkey with TopScan, TopMatch, TpsFix

Clarion 5 is in development with these features:
* 32-bit IDE that was Non-Modal with multiple APP an DCT - (not in C5 was C7)
* New 32-bit compiler does Microsoft standard object code
* Dot Syntax instead of Prop:Xxxx (never happened)
* Property Inspectors like VB (C7?)
* Entity Inheritance like NEW(File)

## C4 - The Big Bang - David Bayliss

A few notes of the insight and humor of DAB "My manager kept asking for an easy way to move from Legacy to ABC OOP. Normally to port a product to OOP takes a long as the original development. Since my manager didn't know what he was asking for he really won't know if he does not get it." DAB went on to describe the C4 Conv utility to move to ABC. it shipped as source so it could be adaptable by users. Thirst party could make plug-in DLLs to convert their products. Can be adapted for mass embed changes.

* One Procedure per Module is absolutely DAFT! Packing them compiles and runs faster. Put related procedures together e.g. Browse and Form.
* ABC Browse is much better than Legacy which refreshes up to 4 times at procedure start. Selected record stays put. Browse can be done with just 10 lines of code in the procedure.
* ABC provides easy Add-Hoc sort orders everywhere: Browse, Report, Process, View
* ABC is "Auto OOP" allows us to use Embeds as we always have yet get OOP code generated.
* ABC Embeds are much more “hierarchical” with simpler names, e.g. all Browse embeds are under one branch
* DAB "it is much better to be vaguely accurate and specifically wrong" (I wrote it downm not sure what it means)
* DAB "We avoid code bloat whereas OOP normally provides it" (ditto)

## The Enterprise Solution - Scott Ferrett

I think this session was about discussing the coming Enterprise Edition that focused on team development and SQL databases. I record these notes:

* Version Control - discussed and showed the benefits of checking in code. a must have for teams
* Data Modeler - Graphical, Error checking, visualize, cascade DB changes
* Dictionary DCT Sync - Written in Clarion code so will be extendable (did not happen?). Much more than a SQL tool can work with all drivers including BTrieve and TopSpeed. Can go from any file type to any other. Can perform file conversion or write the code similar to CFIL.EXE from CPD.
* Deployment Kit - Built Installs e.g. Setup.exe. (I used this and it worked fine, it no longer exists)
* Smart Buffering - Faster and smarter data access by minimizing network traffic. Fat cursors and wide fetches. Caches pages.


## Wrap Up Q&A Session – Bruce Barrington

Always a highlight the final session was hearing the boss reveal some inside info about things that had happened we did not know about, and what was planned for the future. I took a two and half pages of notes that I put some below.

* Enterprise Edition expected by January 1998 in at least Beta form. Price $1500, upgrade $1000
* DCT Sync is the biggest part of EE left to complete
* TPS Toolkit / TopScan will probably be sold separately, may be included in EE
* CW version 2.004 is in beta and will release soon. Required for CWIC.
* Bug Reporting? They are committed to getting one live using CWIC.
* MS SQL driver release? - It has been in Alpha for a few months. Good but not working with big record counts.
* SQL Anywhere driver? - Yes but it will really use ODBC under the covers.
* Smart buffering release? Will be in C4, as well as better ODBC driver.
* COM and DCOM supported and easy like VB? Answer: Actively discussing.
* CWIC in C4 will not support ABC initially
* DAB will be writing for Clarion Online
* Will Debuggers improved? - Minor fixes only. (still true, written in Modula 2)
* Can other 3rd debuggers be used? - NO
* Will Editor be improved? - Not in C4
* Will C4 EE have SQL optimized templates? - YES
* C4 improved ASCII File Viewer / Browse? - NO (fyi: C8+ PREVIOUS for ASCII/BASIC so can use Browse template)
* C4 new feature LIKE() is in DCT and Procedure Data.
