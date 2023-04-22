#ITY - Projekt 5
#Autor: Matej Keznikl
#Fakulta: Fakulta informačných technológií VUT v Brne (FIT VUT)

NAME = proj4

to_pdf: *.tex
	pdflatex *.tex
	pdflatex *.tex

.PHONY: to_pdf clean zip
	
clean:
	rm -f $(NAME).out $(NAME).ps $(NAME).aux $(NAME).dvi $(NAME).log xkezni01.zip

zip:
	zip xkezni01.zip *