#ITY - Projekt 3
#Autor: Matej Keznikl
#Fakulta: Fakulta informačných technológií VUT v Brne (FIT VUT)

NAME = proj3

.PHONY: to_pdf clean

all: to_pdf clean

to_pdf:$(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex
	dvips  -t a4 $(NAME).dvi
	ps2pdf $(NAME).ps

clean:
	rm -f $(NAME).out $(NAME).ps $(NAME).aux $(NAME).dvi $(NAME).log