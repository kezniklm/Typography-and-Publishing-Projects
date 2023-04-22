#ITY - Projekt 5
#Autor: Matej Keznikl
#Fakulta: Fakulta informačných technológií VUT v Brne (FIT VUT)

NAME = proj5

to_pdf:$(NAME).tex
	pdflatex $(NAME).tex
	pdflatex $(NAME).tex

.PHONY: to_pdf clean zip
	
clean:
	rm -f $(NAME).out $(NAME).ps $(NAME).aux $(NAME).dvi $(NAME).log xkezni01.zip

zip:
	zip -r xkezni01.zip *
