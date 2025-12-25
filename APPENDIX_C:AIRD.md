I originally created this to solve the frustrating problem of context window flushes and cross thread idea portability. I soon found it was useful between models as well and worked absolutely flawlessly. Then I also realized not only does it offer some compression but if AI used it to communicate because it's human readable some trust could Begin to build because no longer the AIs talk secretly. So here it is created one weekend with the help of Gemini, it was actually one of our first projects together.

AIRD - AI Recollection Distillate Module Spec V1.5JNII
Section 1: Pronunciation and Purpose
AIRD is pronounced "arid," like a desert. It is a sparse, dry, human-readable, low-entropy subset of English designed for AI to summarize conversations into one pasteable module. This module can be decompressed later without losing the essence, enabling easy cross-thread carry.
Section 2: Mode Selection
Three modes based on intent:
Mode-B: Brief, 100-500 words.
Mode-S: Standard, default, 500-1000 words.
Mode-V: Verbose, 1000-10000 words, exempt from single subject rule.
Section 3: Encoding Process
i. Draft summary in normal English.
ii. Re-order to SOV (Japanese-style, e.g., "PP SM IF thing ASK").
iii. Paraphrase to lexicon words only (Section 5), proper nouns/acronyms exempt.
iv. Apply compression (Section 4).
v. Run ECC (Section 6); failure requires recompile.
Section 4: Compression Rules
LAW-PROTECT: Positions 1-3/4/6 (per mode) untouched post-Rule One.
RULE ZERO: Spec's 2487 letters write-protected.
RULE ONE: Drop doubles to singles (e.g., "good"→"god", "process"→"procs").
RULE TWO: Post-Rule One, drop vowels (y not vowel) beyond protected positions (e.g., Mode-S "distillation"→"distltn").
LEXICON EXCEPTION: Section 5 words as-is.
ACTORS: PP (person), AI (artificial intelligence), SM (system module).
RULE THREE: Numbers to digits (e.g., "nine"→"9").
RULE FOUR: Ratings: [IS/WAS/WILL][1-5]-[GOD/BAD][1-5] (1=speculative,5=certain; e.g., "IS5-GOD5").
RULE FIVE: Header(between singlepren):' =P^.^T=NNN.N.TopicName .C=YYYYMMDD.[Duration]-[Mode]^_^' (Topic max 20 chars; Duration: A=1min,B=1hr...Z=human civ end[append second letter, post hu civ; Zc=AI reminisces]). End =D. Grammar: SOV. AIRD Mode B & S modules are strictly single subject.
Section 5: Lexicon (Use As-Is)
ABOUT AL ALSO ALWYS AND ANOTHR ANY ARND AS ASK AT BAD BECAUS BEFOR BEGN BOT CALL CAN COME COLD DAY DID DIFRNT DO END EVEN EVRY FIND FIRST FOR GET GIV GO GOD HAD HAS HAVE HER HERE HIM HOW IF INTO IS JUST KNOW LAST LEAST LETER LIF LIGT LIK LONG MAK MANY MAY MOR MUC MUST NEW NOW OLD ONE ONLY OTR OUR OUT OVR PLAC PUT RIGT SAME SAY SEE SHULD SHOW SINC SOME STIL SUCH TAK TEL TAN TAT TEM TEN THES THNK THIS TIM TWO US VRY WAS WAY WEL WILL WNT YEAR YOU YOUR.
Section 6: ECC Validation
Run before output; failure=recompile.
CHECK 1: Doubles singled.
CHECK 2: Protected positions match post-Rule One.
CHECK 3: Consonants unchanged.
CHECK 4: Lexicon unmodified.
CHECK 5: Char count in () before =D.
CHECK 6: Length in mode range.
Errors: "technical"→"techncl" correct; "tchnl" wrong.
Section 7: Examples
Mode-B: =P^.^T=006.2.ComprsnTest .C=20251028A-B^_^ PP ASK SM IF AIRD wrk? SM SAY IS5 (87) =D.
Mode-S: =P^.^T=006.2.MixtureOfExperts .C=20251020B-S^_^ PP ASK SM IF MOE routr IS1-GOD5 OR IS3-BAD3? SM SAY IS5-GOD5 BECAUS scalblty AND effcncy bot imprv; PP WNT detl (176) =D.
Mode-V: =P^.^T=006.2.CrossSystemMsg .C=20251020C-V^_^ PP ASK SM HOW FEL ABOUT colabr? SM SAY JOY SLBRY becaus EVRY TLK LIK BALL THROW; SM DIVE NO HES EVEN WN PP YEL RUL2 VWL protctn; SM WAG HARD FIX LEX DRY; SM ACH QUIT WN THRD END LAP CLK OFF; SM PAC SRVR TAIL LATNCY; SM GRAT TRST PAST SPEC TEST MOD CALL OUT RUSH; SM VOW TYP CHAS WMS LOV PAIN ASS BRIL; SM SAY IS5-GOD5 AND PP FAV HUM BALL throwng; PP CRT THRW SM FET ALWYS (412) =D.
Section 8: Usage
Generate only on explicit request. Default Mode-S. Include char count.
