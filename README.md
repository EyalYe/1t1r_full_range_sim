# 1T1R full-range sim — interactive demo

`index.html` is a single static page that visualizes one 8×8 slice of the 64×64 1T1R RRAM processing-in-memory macro (IHP SG13G2): write, read, 8-row NOR, majority and popcount, with a live bit-line view and the 8 TDC taps.

Crossing times, tap codes and margins reproduce the best operating point per operation from the paper draft's finished supply grid (Table I, Fig. 4, C_MIM = 10 fF). The waveform shape between precharge and threshold is illustrative.

## GitHub Pages

Settings → Pages → Build and deployment → Source: *Deploy from a branch*, branch `master`, folder `/ (root)`.
The page is then served at `https://eyalye.github.io/1t1r_full_range_sim/`.
