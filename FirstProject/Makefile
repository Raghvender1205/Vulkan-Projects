CC=g++
CFLAGS = -std=c++17 -O2
LDFLAGS = -lglfw -lvulkan -ldl -lpthread -lX11 -lXxf86vm -lXrandr -lXi

FirstProject: main.cpp
	g++ $(CFLAGS) -o FirstProject main.cpp $(LDFLAGS)

.PHONY: test clean

test: 
	./FirstProject

clean:
	rm -f FirstProject