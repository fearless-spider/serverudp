.cc.o:
	g++ -c -Wall $<

all :	client server

client :client.o
	g++ -o client client.o

server :server.o
	g++ -o server server.o
run-server :
	./server
run-client :
	./client
clean :
	rm -f client.o
	rm -f client
	rm -f server.o
	rm -f server
