all: smooth

smooth: smooth.o glm.o gltb.o
	gcc smooth.o glm.o gltb.o -o smooth -lglut -lGL -lGLU -lm

smooth.o: smooth.c
	gcc -c smooth.c

glm.o: glm.c 
	gcc -c glm.c

gltb.o: gltb.c
	gcc -c gltb.c

clean: 
	rm -rf *.o smooth
