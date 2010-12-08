# %W% %G% %U%
#
# 1985 makefile
#
# Copyright (c) 1985, Landon Curt Noll & Larry Bassel.
# All Rights Reserved.  Permission for personal, educational or non-profit
# use is granted provided this this copyright and notice are included in its
# entirety and remains unaltered.  All other uses must receive prior permission
# from Landon Curt Noll and Larry Bassel.


SHELL=/bin/sh
WINNERS= applin august lycklama shapiro sicherman

all: ${WINNERS}

applin: applin.c
	cc $? -o $@
august: august.c
	cc $? -o $@
lycklama: lycklama.c
	cc $? -o $@
shaprio: shaprio.c
	cc $? -o $@
scherman: sicherman.c
	cc $? -o $@

clean:
	rm -f core
clobber: clean
	rm -f ${WINNERS}

install: all
	@echo are you kidding'??'
