all: lcm.c
	icc -O3 -xavx -o fim_closed -DLCMFREQ_COUNT_OUTPUT lcm.c -L../cephes_double -lmd
profile: lcm.c
	icc -O3 -xavx -o fim_closed -DLCMFREQ_COUNT_OUTPUT -DPROFILE_MINING lcm.c -L../cephes_double -lmd





