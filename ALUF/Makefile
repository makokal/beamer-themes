all:    build make

build:
	latexmk -pvc -f -pdf -quiet -latex=xelatex -quiet aluf_sample.tex

clean:
	latexmk -c
	rm -rf *.lol
	rm -rf *.bbl
	rm -rf *.aux
	rm -rf *.out
	rm -rf *.fdb*
