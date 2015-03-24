#
# Makefile for Pandoc Slideshow
#

INPUT="slideshow.md"
TARGET="slideshow.pdf"

all: $(TARGET)

clean:
	rm $(TARGET)

$(TARGET):
	pandoc -t beamer $(INPUT) -o $(TARGET)

