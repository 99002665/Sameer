all:all.out
all.out: operations.o library_test.o
	g++ $^ -o $@ -lgtest -lgtest_main -lpthread
%.o:%.cpp
	g++ $< -c
clean:	
	rm -rf *.o *.out
run:all.out	
	./all.out
