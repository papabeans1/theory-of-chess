all: chess-rules.pdf

chess-rules.pdf: chess-rules.tex
	mkdir -p build
	pdflatex --output-directory=build chess-rules.tex

clean:
	rm -rf build chess-rules.pdf