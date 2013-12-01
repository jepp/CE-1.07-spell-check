CE-1.07-spell-check
===================

A community effort to spell check the FTL Captain's Edition mod for the roguelike game FTL by Subset Games.

Welcome traveler. I guess you came here from the FTL forum and know what this is about. 
If not, than you might want to have a short rundown of what is going on here.
Over the last months I have created a quite huge modification of the froguelike game FTL by Subset Games. You can find information on the mod here:
http://www.ftlgame.com/forum/viewtopic.php?f=11&t=15663
The mod contains quite a bit of text for the player to read, but English is not my mother tongue and eliminating all the types has been requested quite often.
So I uploaded the files containing most of the texts on github to allow multiple people to participate in checking the mod.
I have no clue about real coding, FTL moding mostly works by editing simple xml files. 
So this whole "project" is really just about spell checking a lot of small text snippets contained in xml capsules.



House rules:

1. Changes you make in the files have the potential to make the mod unplayable very easily. 
Act responsible and observe this rules, else this effort to spell check CE will not work.

2. Only spell check things within text tags. Everything else might mess up the mod structure. Stray characters outside of tags cause problems and are hard to locate afterwards.

3. If you feel that some text should be rephrased than be sure to understand what it is ment to do/mean. Funky exmample: Texts after choice tags are options the player can take, they don't explain what just happend. Try to keep an eye on the (xml) context of the texts and don't compleately rephrase things if it is not absolutely necessary.

4. If you have to rephrase things, do not exeed the number of characters the text originally had, 
specially when the text was already pretty long. Too long texts can cause the game to crash on text load. Not cool.

5. Don't add intent or any kinds of breaks in the text. As far as we can tell, FTL event texts need to be pure flowtext to work correctly.

6. Never write anything outside of text tags. Stray characters outside of tags cause problems and are hard to locate afterwards.

7. Please never make any direct changes in the choices that let the player us the combat augments. This includes changing the intend of this choices, which is usually not properly done. Why is the intend so sloppy for this parts of the code you ask? Because this choices are a single template tha has been spam copied into the entire eventfiles via find and replace. Making any changes to these parts of the code will remove my ability to control these choices globally via the same technique. Bad if you ever want to see more combat augments integrated. If you have suggestions how these choices could be improved, you can post them as comments and I can change them globally.

8. This repository is for spellchecking, not for sneaking changes you like to see into CE. The mod is free to use for anyone. If you have your own vision how of it should be than you can simply take a copy, make your modifications and publish it. Here is not the place for this though and githubs revision control will let me see anything you do anyway.




Thank you all for your help
sleeper_service
