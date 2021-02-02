# Tengai Makyou: Ziria Haruka naru Jipang - Menu Translation
Tengai Makyou: Ziria Haruka naru Jipang is quite a unknown and rare Japanaese Xbox 360 exclusive. Since im kinda of a sucker for 1) Japanaese Xbox 360 Games 2) Far East of Eden (IV is just top tier) this game was always a no brainer for me. This perticular game is kinda of a mystery to alot of people, some even forget it exsist, its not an amazing remake but it good enough. Oh ya forgot to mention it is a remake to the game of the same name but for PC Engine. Also this game can be quite hard to come by, even on japanese markets it fetches for well over $200 USD, so its tough to come by. However with all that said, i still enjoyed the game and thought its worth a try to translate the menus for the .01% of people who will ever play it. With that said all Far East of Eden games have tons of story to them and a crazy amount of text, so this is the best ill manage for now. 

Games files are pretty easy to understand, The game has a three folder structure one of them containing a AFS Package, and the other two are Scripts/Maps and Movies. All files can easily be extracted from the AFS package with quickbms and AFS script. After you extract the package you have  Sounds, movies, and music are all in ADX for sounds, and SFD for movies, all of which play natively to VLC.

As you might see the game is using two byte kanji for everything which gives full width english, which limits the room on the menu. 01 00 will signify a break line but only so much can be put on there. Will need to work on AMS hacking it or trying to inject a new font file. Which when extracted you get a font_dds.cns file which is whats loaded by the game. Figuring out the cns format should allow for a new font to be used. Have also been unable to locate the pointer tables to maybe find free space to allow for longer text (though honestly it wont help much unless the full width text is fixed)

Requirement:
- Ability to play unencrypted XEX files.
- Know how to patch games?
- Expectations for not the best quality translation, Limited character space.

Todo:
- Hack Font to look better
- Tons and Tons of Text to Translate & Inject


![Battles Translated](https://s3.yuvi.app/GamePreservation/FarEastofEdenZiria/FEOEZ1.png)
![Menu Translated](https://s3.yuvi.app/GamePreservation/FarEastofEdenZiria/FEOEZ2.png)
