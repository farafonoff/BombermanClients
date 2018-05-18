.PHONY: all

all: easywsclient GameClientBomberman.o

easywsclient: easywsclient/easywsclient.o
	$(MAKE) -C easywsclient


GameClientBomberman.o: GameClientBomberman.cpp
	g++ -c GameClientBomberman.cpp -std=c++11 


