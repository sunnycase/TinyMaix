TOP_DIR = ../../../../..
sinclude $(TOP_DIR)/tools/w800/conf.mk

CSRCS = tm_layers.c \
        tm_layers_O1.c \
        tm_model.c \
		tm_stat.c

ifndef PDIR
GEN_LIBS = libsrc$(LIB_EXT)
endif

#DEFINES +=

sinclude $(TOP_DIR)/tools/w800/rules.mk

INCLUDES := $(INCLUDES) -I $(PDIR)include
PDIR := ../$(PDIR)
sinclude $(PDIR)Makefile