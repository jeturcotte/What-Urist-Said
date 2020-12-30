# What Urist Said

This is a public repo for (mostly) additions and (a few) adjustments made to the raw files for dwarf fortress, currently caught up with DF 0.47.04.  It's also a subset of https://github.com/jeturcotte/raw_dwarf_meat, excluding changes to animals, minerals, and minor corrections to some graphics.  Here it's just words.

# Usage

There's no install script, per se.  Just copy these files over to the main /raw/objects/ directory in your expendable copy of dwarf fortress and allow them to overwrite the existing versions.  And poof, any new game you start will come with all the below new words.

# Change log:

## version 0.1.6 ~~ 'further vocabulary VI'

* more language stuff, a lot of which is job and worker related, introducing a basic language system
  * wherein:
    * in dwarven, (word) is the job and (word)it is the worker
    * in elven, (word) is the job and (word)we is the worker
    * in goblin, (word) is the job and (word)ux is the worker
    * in human, (word) is the job and (word)ith is the worker
  * thus adding more words:
    * AMBUSH and AMBUSHER
    * APPRAISE and APPRAISER
    * BOWYER (to supplement and repair BOW)
    * BREWER (to supplement BREW)
    * BURNER (to supplement BURN)
    * CAP (not a job or a worker)
    * CARE and CARETAKER (unique case as both are nouns and verbs at the same time)
    * CARPENTER and CARPENTRY
    * CARVE and CARVER
    * CLEANER (to supplement CLEAN)
    * CLERK (job AND worker... I'll come back and fix this)
    * CLOTH and CLOTHIER (couldn't think of a verb on this one)
    * COMEDIAN (to supplement COMEDY)
    * CONSOLE and CONSOLER
    * CONVERSE and CONVERSATIONALIST
    * CRAFTER (to supplement CRAFT)
    * DESIGN and DESIGNER
    * DISSECT and DISSECTOR
    * DYER (to supplement DYE)
    * ENGINE and ENGINEER
    * ENGRAVE and ENGRAVER
    * FARMER (to supplement FARM)
    * made minor adjustments to existing FISH_NOUN and FISH_VERB to make the latter linguistically consistent with JOB/WORKER additions
    * FLAT
    * FLATTER and FLATTERER
    * made minor adjustments to existing GROW(er) and GROWTH to make both linguistically coinsistent with JOB/WORKER additions
    * HERB and HERBALIST
    * HUNT and HUNTER
    * INTIMIDATE and INTIMIDATOR (and, technically, 'timid')
    * LEATHER and LEATHERWORKER (but not leatherworking because it's not really a verb?)
    * LIAR (to supplement LIE)
    * LYE (but no lye maker, thanks)
    * MACE
    * MASON and MASONRY (seriously... it wasn't in there already???)
    * MECHANIC (to supplement mechanism)
    * MILK and MILKER
    * MILL and MILLER
    * MINER (to supplement MINE)
    * NEGOTIATE and NEGOTIATOR
    * OPERATE and OPERATOR
    * ORGANIZER (to supplement ORGANIZE)
    * PACIFY, PACIFIER, and PACIFIST
    * POTASH
    * PROSPECT and PROSPECTOR 
    * PUMP
    * RECORD (didn't feel like trying to make record keeper a word)
    * SEEK and SEEKER
    * SLATE MINERAL and SLATE TOOL (nother work or worker) 
    * SOAPER (to supplement SOAP)
    * STALK PLANT (not a job or worker, just a plant part)
    * THRESHER (to supplement GRAIN)
    * TRADER (to supplement TRADE)
    * TRAIN NOUN, TRAIN VERB and TRAINER
    * TRAPPER (to supplement TRAP)
    * WEAPON (leaving off smith, etc since that's a word already)
    * WEAVER (to supplement and fix a past addition of WEAVE)
    * WOODWORKER (to supplement WOOD)
    * WRESTLE and WRESTLER
  * and fixing some exisiting words to fit the job/worker system i'm slowing implementing
    * COBBLE and COBBLER adjusted
    * WORSHIP and WORSHIPPER adjusted
  * also fixed FELDSPAR calling itself felspar in game

## version 0.1.5 ~~ 'further vocabulary V'

* on a whim, decided to add to the language files (dont tell me what to do!):
  * Adding adjective 'ruinous' to the verb RUIN_V
  * Fixed PLANET's adjective to be planetary (as opposed to plantary)
  * CIVIL (adj)
  * CIVILIZATION (n,a,v)
  * COBBLE (n,a,v)
  * COBBLER (n)
  * COBBLESTONE (n)
  * Added adjective for TEAR (as in, eyes)
  * TORN (n(tear),a,v)
  * WEAVE (n,a,v)
  * Added 'confederate' as adjective to CONFEDERACY and moved verb away from that to CONFEDERATION instead
  * FEDERATION (federal)
  * SIMPLISTIC (adj)
  * HEGEMONY (separate from HEMEGON) (n,a)
  * UNIT (n,a)
  * FASTING (as in, to fast)
  * FAST (slow already available)
  * VITREOUS (adj, glassy texture)
  * VITRIOL (n,adj, bitter/cruel)
  * HIDE, HIDING (was HIDE, now retasked from hiding/hidden), and uh... TANNER
  * HONE (adj,v, to improve)
  * SHARP (adj)
  * SHARPEN (adj,v)
  * INDIGNITY (n,a)
  * REVOLT (n,v) (combat) not to be confused with REVOLTING (re: disgust)
  * INSULATE (a,v) including insular
  * PHANTASM (n,a); also added adjective to PHANTOM
  * CONTEMPTUOUS (a) as an alternative to CONTEMPT(ible)
  * ORGANISM (n,a) not to be confused with ORGAN
  * Adjusted MORTAL and IMMORTAL to be more useful, including verbage for the latter
  * FATEFUL (a) added as alternative to FATE(d)
  * GLASS (n,a)
  * Added [THE_COMPOUND_ADJ] to all the adjectives related to stony descriptions (granite, etc) and added OBSIDIAN
  * LODGE_ACTION (a,v) to lodge something in something
  * LODGE_PLACE (n,v) a lodge or to lodge for the night somewhere
  * Tinkered a fair bit with the language files in and aroudn terms for nations; confederacy through hegemony, so they had, in most languages, similarities to one another

## version 0.1.5 ~~ 'further vocabulary IV'

* on a whim, decided to add to the language files (because reasons):
  * REPTILE 
  * TURTLE (snake, serpent, lizard already present)
  * AMPHIBIAN
  * OLM (toad, frog already present)
  * SALAMANDER

## version 0.1.4 ~~ 'further vocabulary III'

* on a whim, decided to add to the language files (because reasons):
  * COLONY
  * NEAR & FAR
  * CRYPTIC
  * FRUITFUL (translations take a cue from FRUIT)
  * UNJUST & INJUSTICE (with cues from JUST)
  * MISER
  * SMELT (translation take a cue from MELT)
  * NOBILITY (translations take a cue from NOBLE)
  * SINGULAR (takes a cue from SINGLE)
  * RAPT & RAPTURE
  * SCENE
  
## version 0.1.3 ~~ 'better vocabulary IIb'

* um... so... yeah
  * I went through the ENTIRE language file and fixed things ups
  * It's not complete, but it is MORE complete than the originals
  * There may be some err

## version 0.1.2 ~~ 'further vocabulary II'

* on a whim, decided to add to the language files (because reasons):
  * PROXIMITY
  * APPROXIMATE
  * LEGAL
  * ILLEGAL
  * CRIME
  * CRIMINAL
  * COURT
  * COURTSHIP

## version 0.1.1 ~~ 'further vocabulary I'

* on a whim, decided to add to the language files:
  * Buttes (the flat topped hills)
  * Contracts (legal AND physical)
  * Expansions (physical)
  * Crags
  * Forges