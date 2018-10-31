# hh_change_bw
hare and hounds simulations with various bin widths
All flares have exponential flare shape.
Includes 5 single qpp flares with various periods and damping times: 220365, 172146, 241503, 618098, 748751
Includes 2 flares with 2 qpp: 416568 & 566801
Includes 2 flares with qpp with non-stationary period: 754456 & 801580
All flares were included in hh1 - all controllable parameters were kept the same but the noise realizations will be different

Each flare has 5 different bw available 0.001, 0.005, 0.01, 0.05, 0.1 i.e. all smaller cadence than hh1, where the bw was 1. As the bw was increased every 5th, 10th, 50th, and 100th data point was taken i.e. the data were not smoothed.

Each file contains unitless time and unitless flux. 
