#ITY - Projekt 1 
#Autor: Matej Keznikl
#Fakulta: Fakulta informačných technológií VUT v Brne (FIT VUT)

LOGIN = xkezni01

.PHONY: pdf clean

all: to_pdf clean

to_pdf:$(LOGIN).tex
	latex $(LOGIN).tex
	latex $(LOGIN).tex
	dvips  -t a4 $(LOGIN).dvi
	ps2pdf $(LOGIN).ps

clean:
	rm -f $(LOGIN).out $(LOGIN).ps $(LOGIN).aux $(LOGIN).dvi $(LOGIN).log