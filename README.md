# lband_downconverter
RF downconverter for L-Band satellite work.  Some RTL-SDR dongles have difficulty locking their PLLs at L-band frequencies, and feedline losses are rather significant at those frequencies.

Design: input -> LNA -> bandpass -> mixer + 1.2GHz LO -> LNA -> bandpass (or just lowpass?)
