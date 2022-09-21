# change compiler, flags, and target as needed
FC = ifort
FFLAGS = -FR
TARGET = main

SRCS := $(shell find . -name '*.f')

$(TARGET): $(SRCS)
	$(FC) $(FFLAGS) -o $(TARGET) $(SRCS) 

clean:
	$(RM) $(TARGET)
