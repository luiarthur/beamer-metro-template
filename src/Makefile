maindoc = main

all: build

build:
	latexmk -xelatex $(maindoc).tex

watch:
	latexmk -xelatex $(maindoc).tex -pvc

clean:
	latexmk -c

cleanall:
	latexmk -C
	rm -f *.snm *.nav *.bbl *.log
