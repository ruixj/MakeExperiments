A = before1
A = before2
B = $(A)
all:
#sinclude config.mk

#ifdef C
ifeq ("$(B)","before2")
$(warning I am be included)
sinclude test.h
endif



test.h: test.mk
	$(TOUCH) test.h
sinclude config.mk

all:
	echo $(B)

A = after1
