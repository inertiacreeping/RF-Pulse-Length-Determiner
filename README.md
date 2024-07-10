# RF-Pulse-Length-Determiner
Trying to find out the fucking pulse length of my RF roller blind remote

THEORETICALLY THIS SCRIPT:

Signal Detection and Decoding: captures the RF signal and prints out the raw pulse data and scaled pulse lengths.
Base Pulse Length Calculation: calculates the estimated base pulse length by averaging the raw pulse data.
Signal Structuring: structures the signal by comparing each pulse length to the estimated base pulse length. If a pulse length is less than 1.5 times the base pulse length, it is considered '1', otherwise '0'.
