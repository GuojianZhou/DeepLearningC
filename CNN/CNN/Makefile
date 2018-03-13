GPP=g++
CPPFLAG= -O3 -std=c++11
objects= main.o minst.o cnn.o mat.o 

minst_cnn: $(objects)
	$(GPP) $(CPPFLAG) -o minst_cnn $(objects)
main.o: main.cpp
	$(GPP) $(CPPFLAG) -c main.cpp
minst.o: minst.cpp minst.h
	$(GPP) $(CPPFLAG) -c minst.cpp
cnn.o: cnn.cpp cnn.h
	$(GPP) $(CPPFLAG) -c cnn.cpp
mat.o: mat.cpp mat.h
	$(GPP) $(CPPFLAG) -c mat.cpp

all: minst_cnn

clean:
	rm minst_cnn $(objects)
