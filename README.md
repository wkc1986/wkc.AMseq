# wkc.AMseq
Self-modifying Markov transition matrix sequencer for sliced-buffer playback.

- Slice a buffer into 8 segments
- Next segment depends on current segment
- Feedback changes transition probability: transitions that occur become more likely to recur in the future!

Requires the karma~ external (for now): 

http://www.rodrigoconstanzo.com/2015/05/karma/
