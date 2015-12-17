#Sasha Sirovica 912088932
all: tetris

CXXFLAGS = -g -Wall

Tetromino.o: Tetromino.cpp Tetromino.h
Board.o: Board.cpp Board.h
tetris.o: tetris.cpp

tetris: Tetromino.o Board.o tetris.o
	$(CXX) -o $@ $^ $(LDFLAGS)

clean:
	rm -f *.o tetris
