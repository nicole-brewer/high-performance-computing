# change compiler, flags, and target as needed
CXX = icpc
CXXFLAGS = 
TARGET = main

SRCS := $(shell find . -name '*.cc' -or -name '*.cpp')

$(TARGET): $(SRCS)
	$(CXX) $(CXXFLAGS) -o $(TARGET) $(SRCS) 

clean:
	$(RM) $(TARGET)
