BOARD ?= samr21-xpro
include ../Makefile.tests_common

BOARD_INSUFFICIENT_MEMORY := arduino-duemilanove arduino-leonardo arduino-nano\
                             arduino-uno

FEATURES_REQUIRED = periph_spi

USEMODULE += xtimer
USEMODULE += shell
USEMODULE += shell_commands

include $(RIOTBASE)/Makefile.include
