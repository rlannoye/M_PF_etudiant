
SRC = $(shell find . -name "*.cpp")
BIN = $(SRC:.cpp=.out)

all: $(BIN)

%.out: %.cpp
	$(CXX) -std=c++11 -Wall -Wextra -o $@ $< 

.PHONY: clean

clean:
	rm $(BIN)
