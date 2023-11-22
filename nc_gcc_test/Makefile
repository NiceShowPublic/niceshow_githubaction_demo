.SUFFIXES : .x .o .c .s

CC := gcc

TARGET = nc_gcctest
SRCS := nc_gcctest.c

all:
	$(CC) $(SRCS) -o $(TARGET)

clean:
	rm -f *.o
	rm -f *.x
	rm -f *.flat
	rm -f *.map
	rm -f temp
	rm -f *.img
	rm -f $(TARGET)
	rm -f *.gdb
