# A Spouse Designer for 1.8 aka ksd aka spouse_designer_updated

This is a version of Lrds' <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=2298410092" target="_blank"> A Spouse Designer</a> updated for 1.8.* and later.

Presently this is a work in progress, so some crashes may happen and their may be errors reported in the error.log. Please let me know about such.  

There's a decent chance it won't work in languages other than English because I haven't finished updating  the localisation yet. 

This is a standalone mod rather than a patch since nearly all files are modified. It is almost certainly not compatable with patches for the previous version (Paradox made some significant changes to the GUI as well as adding the additional engine level checks that cause the game to crash if they are failed in 1.6.1* ).  Please do not update your Compatches until this is actually finished.  

FAQs:

1: How do I Edit Characters after Game Start:
Set the Spouse Designer: Designer After Game Start rule to Enabled before you start. 
2: Where is the option to Edit my Spouse/Child/Etc ?
a) See 1 
b) Please see the Screen Shots for this mod, which show starting from the Starting Screen where all Edit Options are for a New Game and for a Game In Progress. 

*1.8 has included the ability to Load / Save rulers so this mod is not backwards compatible with versions before 1.8.

Changes:
- Doesn't always Crash when editing a Spouse/(unlanded) Child
- Generated Spouse use similar rules to the ones used by the Generate Family game option, so if you don't edit them they'll still be reasonable characters 
The above means that:
a) Female Rulers Generated Spouse start matrilineally married 
b) Same Sex Spouse can be generated under the conditions they would be in game.  
- Generated Children to use similar rules to those used for the Family Generation game rule
The above means that:
a) If you generate children for long dead parents they can be centuries old.  
b) There should be a natural spread in the ages of children, as long as you keep it to a reasonable number and keep in mind the ages of the older siblings but if you create too many, they will cluster at the youngest possible age
[strike]c) If you generate children who do not stand to inherit a Dynasty they *WILL* be created but they *WILL NOT* be visible on the Character Selection/Family screen. [/strike] - Fixed
- No longer allows editing/divorcing/removing Spouse/Children after Game Start (same as Ruler Designer) (by Default, this can be changed with a Game Rule)
- Prevent changing marriage type of/divorcing Landed Spouse
- Prevents editing/removing Landed Children (bringing them into alignment with Landed Spouse)
- Spouse options should no longer display for characters who can't marry 
- Dead characters are now explicitly blocked from (even more) modifications that would fail anyway. 
- Generated Spouses/Children should now always have a location and should usually find an Employer (unless their existing spouse (for spouse)/living parents (for children) are Wanderers or they are far removed from living characters/cultures/faiths in which case they will start as Wanderers)
- Add Game Rule to allow Editing after Game Start
- Add Game Rule to control Editable Characters (Playable Rulers/Ruler/Any*)
- It is no longer possible to remove Children while they still have Children (you need to remove any Children they have first)  (This is to keep House / Dynasty maps somewhat sensible)
- Display of Children in View/Edit Family updated.  All children are now displayed (even if they do not share a dynasty with the Selected Character or the Primary Spouse or even if they are low born)
-Updated the UI a bit, to move all editing into the Family screen and replace the Edit Ruler button with an Edit/View Family button.  This may have caused some regressions/errors, so let me know. 
- Uploaded some Screenshots showing where everything is currently locatged.

* Editing Unlanded Characters is probably not very useful at the moment because relationships are not preserved, but it does allow you to generate Custom Guests by editing a character in the correct location.  I do have some future plans for preserving relationships as an option which should make this more useful.

To Do:
- Fix some post editing stuff for Spouses/Children that doesn't account for the possibility of matrilineal marriages / same sex marriages. 
- Block Editing of Spouse/Children for Uneditable Characters
- Clean up Selected Character Display (fix Overlap of Difficulties / Difficulty / Family Info / Spouse Info )
- Prevent Edited Spouse/ Children that are illegal (invalid marriages or children too old) in the Ruler Designer window. (Also: Block or Convert Too young spouses to Betrothal, depending on which works better) 
- Allow for creation of Betrothed for children  (maybe?, need to check how the game handles that)
- Option to preserve Dynasty 
- Option to preserve Relationships (relatives, friends/rivals , soulmates/lovers (if valid), Court + Council positions / Employment. etc ) 
- Consider what is Invisible vs what is Disabled. 
- Tooltips to explain disabled stuff (?)
- Finish localisation for supported non-English language
