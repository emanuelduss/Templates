#
# Makefile for Pandoc Document
#

INPUT="document.md"
TARGET="document.pdf"

all: $(TARGET)

clean:
	rm $(TARGET)

$(TARGET):
	pandoc -f markdown $(INPUT) --toc -N --variable "date=`date '+%Y-%m-%d %H:%M'`" -o $(TARGET)
