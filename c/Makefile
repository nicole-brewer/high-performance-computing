# change compiler, flags, and target as needed
CC = icc
CFLAGS = -std=c99
TARGET = main

SRCS := $(shell find . -name '*.c')

$(TARGET): $(SRCS)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRCS) 

clean:
	$(RM) $(TARGET)
