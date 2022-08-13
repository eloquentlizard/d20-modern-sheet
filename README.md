# d20-modern-sheet
Rewrite of the roll20 sheet for both better functionality and to fit the setting/homebrew I'm writing for my upcoming game.

I'm condensing skills and making the macros a little bit better for my group & more like what most of us are accustomed to.

##Skill changes

- many skills condensed
- knowledge, perform, craft, speak/read/write language (now linguistics) have "specializations" which are 2 skill points per. If you don't have a relevant specialization when you make your check (no sub-skills, just a global skill), you take a -6 penalty and have a cap on the kinds of DCs you can hit (much like being untrained). Simplifying the skill table is just going to make life easier for everyone
- skills are either class skills or not class skills, no variance per class
- all skills are 1 skill point per rank, but max ranks are still enforced

##To-do

- add appearance score stuff. appearance doubles as physical attractiveness (comeliness a la Hackmaster) as well as a replacement for reputation score, which isn't going to be a part of per-class advancement
- fix ability check and saving throw macros to use the skill-roll templates
- make the skill table not look like hot garbage & allow "specializations"
- fix class statistic input fields to handle decimals properly such that we can have players' bab/saves/def scaling properly w/o penalties for required multiclassing
- - if possible/not excessively difficult, perhaps having drop-downs for progression rates instead?
- make inventory slightly better, at least with individual items and a few stats like purchase dc and weight
- - important that I not go ham on this, though, as it doesn't need to be fancy as to take away from gameplay
- macros need to not be ``/em`` blocks anymore. We did that back before roll20 had character sheets, and there's already a template set up in the sheet, so we can just reuse that

##Maybes

- skill tricks from 3.5's Complete Scoundrel? maybe? I need to look over them again; it's been a few years...
- revamp spell/feat/talent blocks. they're very minimal atm, but maybe they should stay that way?
- - sometimes less really is more---important thing to remember!
- add markers for feats/talents/spells for them being bonuses?
- - like just a checkbox that adds the appropriate "B" superscript like you see on monster entries
- spell/day calculations (w/ bonus spells)
- add a little more flavor to the templates because flavor can go a long way
- - no decision on exactly how to do this or what to do, though...