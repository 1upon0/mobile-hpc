SHELL=/bin/bash
OPTS = -std=c++11 $(shell pkg-config libusb-1.0 --libs --cflags)
print:
	g++ print.cpp $(OPTS) -o print