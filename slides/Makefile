MAIN=webinar.tex
SOURCES=*.tex
TARGET=$(MAIN:.tex=.pdf)

all: $(TARGET)

$(TARGET): $(SOURCES)
	pdflatex $(MAIN)
	pdflatex $(MAIN)

clean:
	-rm -f $(TARGET) *.log *.aux *.nav *.snm *.toc *.out *.vrb
