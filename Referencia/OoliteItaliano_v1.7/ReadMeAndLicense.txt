Oolite Italiano
Italian Localization Oolite eXpansion Pack v1.7.


INTRODUCTION
------------
This is the seventh version of the first ever localization expansion pack for Oolite (note: the fifth version was never released to public). When installed, it will change the language used in the game to Italian. It is intended for Italian players who would prefer the game in their native language. It also demonstrates a way to utilize the Oolite multilingual capabilities and may serve as an example for users who would like to contribute other language localization packs. It requires Oolite v1.77 or later to function properly.

The idea behind this OXP was to use externalized (i.e. editable outside of the game engine) strings for every single game element, taking into account grammatical and syntactical differences between the source (English) and target (Italian in this case) languages. Many of the game strings were already externalized, so the task was to complete the implementation that Giles Williams had started. Additionally, parts of the game engine had to be modified to accommodate various non-English language idioms and enable proper translation. It has been a difficult and laborious effort, involving more than one persons and this is the result of it all.


INSTALLATION
------------
The zipped file you donwloaded contains this file and a folder named OoliteItaliano_v1.6.oxp. You will need to unzip the contents of the zipped file into a temporary folder. It is important that you maintain the tree structure of the contents when you decompress. Refer to the instructions of your decompression software for information on how to ensure this.

Once decompressed, you will need to move the entire OoliteItaliano_v1.6.oxp folder inside your Oolite AddOns folder. For Windows users, the AddOns folder is located at [OoliteInstallDir]\AddOns. After having done that, launch the game. You should be able to see the Italian text already in the rotating Cobra screen. This means that the OXP has been successfully installed. If you do not see the Italian text, exit Oolite and restart it while holding down the Shift key. This will force the game to rebuild its cache and include the new OXP information in it, but normally this should not be necessary. Just placing the OXP folder in AddOns and launching the game should work without problems on a typical Oolite installation.


NOTE ABOUT THE TRANSLATIONS
---------------------------
You will find out soon that the planet descriptions in Italian do not correspond exactly to the planet descriptions in English. This is because of i) the way the game engine works when generating description strings and ii) because of the different syntax between Italian and English languages. To make these coincide, we must either recode the description generating part of the engine (herculean task and the result does not justify the effort) or recode the Italian language (impossible for obvious reasons). Since the planet descriptions are there to create ambience, it was decided that priority would be given to making the descriptions understandable and ensuring as much as we can that they make sense, rather than making them exact translations of the originals. However, it should be noted that the planet descriptions in Italian use the exact same general description generation algorithm as the original English equivalents.

Also, certain words have not been translated precisely from English to Italian and somewhat different variants have been used. This is because Italian is inherently more complex than English and the game engine creates strings that rely on the syntactical simplicity of English (e.g. plural in English is created by just adding 's' at the end of a noun, but in Italian there may be different plural types depending on the gender). However, I am confident that these changes will not affect the atmosphere of the game and will still allow native Italian speakers to enjoy it fully.


REPORTING PROBLEMS
------------------
If you discover bugs, problems or have a proposal or recommendation with regards to this OXP, please let us know. You can use the Oolite Bulettin Boards at www.aegidian.org/bb for reporting.


KNOWN ISSUES
------------
This OXP resets the HUD used on the player ship to the Italian version of the original HUD distributed with the core game. If you are using a different HUD, be aware that it may be overriden by the HUD specified in OoliteItaliano, depending on the loading order of the OXPs.


THANKS AND ACKNOWLEDGMENTS
--------------------------
This OXP has been the result of combined effort by quite a few people. Many thanks go to:
 - Ahruman, for implementing 8-bit encoding support in Oolite, making all this a possibility.
 - Commander McLane for pointing out many of the technical difficulties involved in producing a localized modification and proposing solutions, many of which ended up in the main game engine.
 - Kaks for the support and taking time to review in detail the test versions of this OXP.
 - dajt for providing me with information on localization based on past experience.
 - Stefano Pasquini, Fabrizio Martini and Antonio Campisi for taking my hopeless initial attempt at translating and transforming it into actual Italian language. Grazie mille guys!
 
 
another_commander
06 January 2012



LICENSE
-------
This work is licensed under the Creative Commons Attribution-Noncommercial-Share Alike 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/3.0/ or send a letter to Creative Commons, 171 Second Street, Suite 300, San Francisco, California, 94105, USA.