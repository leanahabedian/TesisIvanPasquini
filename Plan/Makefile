
plan: 
	@echo "Compiling"
	TEXINPUTS=./style//:$(TEXINPUTS) pdflatex --interaction batchmode propuesta.tex > /dev/null; \
	TEXINPUTS=./style//:$(TEXINPUTS) pdflatex --interaction batchmode propuesta.tex > /dev/null; \
	rm -f *.toc *.out *.aux *.log
	@echo "Done"

clean:
	rm -f propuesta.pdf 

