CXX=g++
all: one-zero.o
	$(CXX) one-zero.o -o one-zero.exe
clean:
	rm *.o one-zero.exe
test: all
	./one-zero.bats
