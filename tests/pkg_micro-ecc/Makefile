include ../Makefile.tests_common

BOARD_INSUFFICIENT_MEMORY := arduino-duemilanove arduino-uno

USEMODULE += hashes
USEPKG += micro-ecc

TEST_ON_CI_WHITELIST += all

include $(RIOTBASE)/Makefile.include

test:
	tests/01-run.py
