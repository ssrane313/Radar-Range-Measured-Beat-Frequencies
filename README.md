# range-using-measured-beat-frequencies
complete the TODOs to calculate the range in meters of four targets with respective measured beat frequencies [0 MHz, 1.1 MHz, 13 MHz, 24 MHz].


% Note : The sweep time can be computed based on the time needed for the signal to travel the maximum range. In general, for an FMCW radar system, the sweep time should be at least 5 to 6 times the round trip time. This example uses a factor of 5.5.

Tchirp = (5.5 *2 * Rmax) / c

Dres​= c / (2 * Bsweep)

R = 2 * Bsweep​cTs​fb​​

speed of light, c = 3*10^8 m/s^2

range resolution, Dres = 1 m

radar maximum range, Rmax = 300 m

range of targets, calculated_range

chirp bandwidth, Bsweep
