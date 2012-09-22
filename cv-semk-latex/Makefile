TARGET=cv-sreejith-k.en.pdf

all: $(TARGET)

%.pdf: %.ps
	ps2pdf14 $<

%.ps: %.dvi
	dvips -Ppdf -G0 $< -o $@

%.dvi: %.tex
	latex $<

readme:
	pandoc -s cv-sreejith-k.en.tex -o README.md

clean:
	rm -f *.log *.aux $(TARGET) *.ps *.dvi

