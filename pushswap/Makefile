.PHONY: all bonus clean fclean re
NAME = push_swap
NAME_BONUS = checker

SRC_BONUS =	checker_bonus.c  check.c  push.c  reverse.c  rotate.c sort100.c sort3.c sort500.c swap.c  sort.c split.c tools.c get_next_line.c get_next_line_utils.c
SRC =	check.c  push.c  push_swap.c reverse.c  rotate.c sort100.c sort3.c sort500.c swap.c  sort.c tools.c split.c
OBJECT = $(SRC:.c=.o)
OBJECT_BONUS = $(SRC_BONUS:.c=.o)

all : $(NAME)

$(NAME):
	@gcc -Wextra -Werror -Wall $(SRC) -o push_swap

bonus:
	@gcc -Wall -Wextra -Werror $(SRC_BONUS) -o $(NAME_BONUS) 
clean:
	@rm -f $(OBJECT) $(OBJECT_BONUS)
fclean: clean
	@rm -f $(NAME) $(NAME_BONUS)
re: fclean all bonus