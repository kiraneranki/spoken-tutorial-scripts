#
# Makefile 
#
PDFLATEX = pdflatex
FILE = slides

all:
	${PDFLATEX} ${FILE}.tex

clean:
	@echo "Cleaning up..."
	-rm -rvf *~ \#*
	-rm -rvf ._*
	-rm -rvf .~*

distclean:
	@echo "Cleaning all..."
	-rm -rvf *~ \#*
	-rm -rvf ${FILE}.pdf
	-rm -rvf *.aux 
	-rm -rvf *.log *.vrb *.toc *.nav *.snm *.out

