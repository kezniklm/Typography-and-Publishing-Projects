#ITY - Projekt 4
#Autor: Matej Keznikl
#Fakulta: Fakulta informačných technológií VUT v Brne (FIT VUT)

NAME = proj4

.PHONY: to_pdf clean zip

all: to_pdf

to_pdf:$(NAME).tex
	latex $(NAME).tex
	bibtex $(NAME).aux
	latex $(NAME).tex
	latex $(NAME).tex
	dvips -sPAPERSIZE=a4 $(NAME).dvi
	ps2pdf $(NAME).ps
	
clean:
	rm -f $(NAME).out $(NAME).ps $(NAME).aux $(NAME).dvi $(NAME).log

zip:
	zip $(NAME) *