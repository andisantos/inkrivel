all:
	mkdir -p bin
	g++ main.cpp gl3w/gl3w.c -o bin/main -lglfw -lm -ldl -lpthread -lSDL2 -lSDL2_mixer -lcurl -Wno-write-strings -lGL -lGLEW

run: all
	./bin/main
