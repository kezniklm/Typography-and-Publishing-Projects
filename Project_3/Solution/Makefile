#ITY - Projekt 3
#Autor: Matej Keznikl
#Fakulta: Fakulta informačných technológií VUT v Brne (FIT VUT)

NAME = proj3

.PHONY: to_pdf clean zip

all: to_pdf

to_pdf:$(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex
	dvips  -t a4 $(NAME).dvi
	ps2pdf -sPAPERSIZE=a4 $(NAME).ps

clean:
	rm -f $(NAME).out $(NAME).ps $(NAME).aux $(NAME).dvi $(NAME).log

zip:
	zip $(NAME) *