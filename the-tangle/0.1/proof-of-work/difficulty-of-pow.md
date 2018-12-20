# Difficulty of Proof of Work

The difficulty of the PoW is set by a variable called Minimum Weight Magnitude (MWM). This refers to the number of trailing zeros (in trits) in transaction hash. MWM is proportional to the difficulty of the Proof of Work. The device which does the PoW will bruteforce the transaction hash to find a \`nonce\` that has the correct number of trailing 0's. Every extra trailing zero to be found will increase the difficulty of PoW by 3 times.