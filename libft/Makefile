# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: mchamayo <marvin@42.fr>                    +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/11/08 15:34:21 by mchamayo          #+#    #+#              #
#    Updated: 2018/12/10 15:04:29 by mchamayo         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a
SRC = ft_isalnum.c ft_itoa.c ft_memcpy.c ft_putchar_fd.c ft_putstr.c \
	  ft_strcmp.c ft_striter.c ft_strmap.c ft_strnequ.c ft_strstr.c \
	  ft_isalpha.c ft_memalloc.c ft_memdel.c ft_putendl.c ft_putstr_fd.c \
	  ft_strcpy.c ft_striteri.c ft_strmapi.c ft_strnew.c ft_strsub.c \
	  ft_isascii.c ft_memccpy.c ft_memmove.c ft_putendl_fd.c ft_strcat.c \
	  ft_strdel.c ft_strjoin.c ft_strncat.c ft_strnstr.c ft_strtrim.c \
	  ft_atoi.c ft_isdigit.c ft_memchr.c ft_memset.c ft_putnbr.c ft_strchr.c \
	  ft_strdup.c ft_strlcat.c ft_strncmp.c ft_strrchr.c ft_tolower.c \
	  ft_bzero.c ft_isprint.c ft_memcmp.c ft_putchar.c ft_putnbr_fd.c \
	  ft_strclr.c ft_strequ.c ft_strlen.c ft_strncpy.c ft_strsplit.c ft_toupper.c \
	  ft_isalnum.c ft_lstnew.c ft_lstdelone.c ft_lstdel.c ft_lstadd.c \
	  ft_lstiter.c ft_lstmap.c
CFLAGS = -Wall -Wextra -Werror -c -I
OBJECTS =${SRC:.c=.o}

$(NAME): 
	gcc $(CFLAGS) $(SRC)
	ar rc libft.a $(OBJECTS)
	ranlib libft.a

all: $(NAME)

clean:
	rm -f $(OBJECTS)

fclean: clean
	rm -f $(NAME)

re:	fclean all

.PHONY: all clean fclean re
