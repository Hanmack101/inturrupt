# inturrupt
learning about interrupts
suggestions to try 

- use millis() not delay (1)
- denounce the buttons (it keeps looping and inturrupting)
- digitalread for buttons instead (do this first - you might not need to denounce)
- multitast to get rid of delay (1.1)
- ditch no tone - using digital read for buttons (denounced) means it's either on or off - stop using notone() (2)
- I think I will re-write the buttons as funtions (if high call 'button one') and have the loops just check if button is high or low (old man on FB suggested this essentially.)


what can I reuse?
sure
- detection and setting of LDR
-notes as separate int variables

maybe
-mapping for the sesors

no
- the if statement in the loop - the conditions are making problems for you and forcing you to use 1) delay and 2) undenounced buttons

Suggestions to ignore
- building a synth 
