CPPFLAGS = $(shell sdl2-config --cflags) $(EXTRA_CPPFLAGS)
LDLIBS = $(shell sdl2-config --libs) -lGLEW $(EXTRA_LDLIBS)
EXTRA_LDLIBS = -lGL
EXE = main

all: $(EXE)

clean:
	rm -f *.o $(EXE)

.PHONY: all clean
