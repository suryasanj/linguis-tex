# linguis-tex
All the scripts one might need for using \TeX for linguistics.

## Description
$\LaTeX$ is great for typesetting, but, in spite of CTAN and community-created 
packages, there are still some niches left to fill. This repository handles those within linguistics. 

## Mapping for Non-Roman Scripts

Typing in other scripts is difficult, especially when most of us are confined to
a QWERTY keyboard. Mapping allows one to type in a commonly used transcription
scheme, outputting Unicode characters in the target script.

*  **Old Tulu (Kannada Script)** ([`tcy.tec`](mapping/tcy.tec))</br>
   This uses the orthography found in Puninchathaya’s editions of the Tulu
   epics. Input may be in ISO 15919 or an alternative transcription scheme (to
   be described in the future). <i>Anusvāra</i>-s are automatically generated
   from homorganic nasal-plosive clusters (eg. `ṇṭ` → `ṁṭ`). The sign for ‹ε› is
   somewhat different from how Puninchathaya uses it, with the <i>virama</i>
   placed after the length marker; there seems to be no aesthetic difference.

*  **Royal Achaemenid Elamite Cuneiform** ([`elx.tec`](mapping/elx.tec))</br>
   Signs are derived from Paper’s (1955) list. Some signs are missing: namely, «kúp», 
   «kar», «šir₇», «zik», and two logograms for man and king. Use the normal 
   transcription scheme for RAE (with ‹z› instead of ‹ṣ›), with one minor change: 
   the vertical and horizontal determinatives, as well as the logogram sign, 
   should be written in Unicode superscript.
