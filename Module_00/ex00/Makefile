CLANG = g++

FLAGS = -Wall -Wextra -Werror -g

NAME = megaphone

SRC = megaphone.cpp

all: $(NAME)
	$(CLANG) $(FLAGS) $(SRC) -o $(NAME)

fclean:
	rm -rf $(NAME)

re:
	fclean all

.PHONY: fclean, all, re