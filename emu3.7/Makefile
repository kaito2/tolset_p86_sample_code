CFLAGS += -Wall -c
OBJS = main.o emulator_function.o instruction.o modrm.c

all:
	make px86

px86: $(OBJS) Makefile
	$(CC) -o px86 $(OBJS)

%.o: %.c Makefile
	$(CC) $(CFLAGS) -o $@ $<
