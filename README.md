OTHire Beta 0.0.2 (Development) [![Build Status](https://travis-ci.org/TwistedScorpio/OTHire.svg?branch=master)](https://travis-ci.org/TwistedScorpio/OTHire)
======

OpenTibia Server for Tibia 7.72

This OTServer is based on OTServ Trunk SVN work (latest stable trunk rev).

The change log can be found to the bottom.

Compatible AAA Znote for OTHire [HERE](https://github.com/peonso/ZnoteOTHire).

## Current othire.exe is outdated, you should compile the newer version with recent changes.

Version Changes
======

  0.0.2 (Development)
  
    - Many items were fixed.
    - Many issues from non Tibia 7.72 were corrected.
    - Fixed violation window, wasn't from 7.72
    - Added items.xml
    - Optimization Changes
    - Linux Compilation
    - Added option for stackable items auto stacking like in newer Tibia versions
    

  0.0.1 (Development)
  
    - Runes
    - Talking (yelling, whispering)
    - Private messaging
    - Rule Violation Channel
    - Bug Reports (Ctrl+Z)
    - Saving & Loading Players
    - House System
    - House Paying through Bank account or depot balance
    - Premium System
    - Skull System (to use compile with __SKULL_SYSTEM__)
    - Anti-Magebomb (attack delay when logging in)
    - Sharing Experience when in party (code is there, implementation is needed through talkactions)
    - GM Invisibility
    - Avesta Spells
    - Players have bank accounts
    - OTServ Trunk Movements (removed unused code)
    - OTServ Trunk Talkactions (removed unused code)
    - Faster OTBM map reading, reading a 120 mb real map in 4.3 seconds, compared to 5.5 seconds RealOTs's Avesta.
    - No more (return TRUE) (if isPremium(cid) == TRUE). Thanks to newer LUA core code
    - Many more
    - ... Everything as in OTServ Trunk
