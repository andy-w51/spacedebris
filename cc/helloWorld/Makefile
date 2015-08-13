SOURCES = main.cc
EXEC = hello

CXX = g++
CPPFLAGS = -Wall
CXXFLAGS =
LDFLAGS =

OBJECTS = $(SOURCES:.cc=.o)

all: $(SOURCES) $(EXEC)

$(EXEC): $(OBJECTS)
	$(CXX) $(LDFLAGS) $< -o $@
	$(RM) $<

.PHONY: clean

clean:
	$(RM) $(OJECTS) $(EXEC)
