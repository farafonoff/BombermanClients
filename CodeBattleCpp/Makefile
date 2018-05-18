client: lib CodeBattleCpp/CodeBattleCpp.cpp
	g++ -std=c++11 -pthread CodeBattleCpp/CodeBattleCpp.cpp CodeBattleCppLibrary/GameClientBomberman.o CodeBattleCppLibrary/easywsclient/easywsclient.o -I./CodeBattleCppLibrary/ -o client

.PHONY: lib

lib:
	$(MAKE) -C CodeBattleCppLibrary

