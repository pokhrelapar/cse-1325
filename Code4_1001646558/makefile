#Apar Pokhrel, 1001646558

SRC1 = Code4_1001646558.cpp
SRC2 = TrickOrTreater.cpp
SRC3 = House.cpp
OBJ1 = $(SRC1:.cpp=.o)
OBJ2 = $(SRC2:.cpp=.o)
OBJ3 = $(SRC3:.cpp=.o)
EXE = $(SRC1:.cpp=.e)

CFLAGS = -g -std=c++11 -pthread


HFILES = TrickOrTreater.h House.h


all : $(EXE)
 
$(EXE): $(OBJ1) $(OBJ2) $(OBJ3)
	g++ $(CFLAGS) $(OBJ1) $(OBJ2) $(OBJ3) -o $(EXE) 

$(OBJ1) : $(SRC1) $(HFILES)
	g++ -c $(CFLAGS) $(SRC1) -o $(OBJ1)

$(OBJ2) : $(SRC2) $(HFILES)
	g++ -c $(CFLAGS) $(SRC2) -o $(OBJ2)

$(OBJ3) : $(SRC3) $(HFILES)
	g++ -c $(CFLAGS) $(SRC3) -o $(OBJ3)
	
	

	
	



 
