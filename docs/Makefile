# Latex compile script
# Created by Anoop Chandran
# Last modified: 22-12-2018 14:41 
# Usage : 
# 		1) make PROJECT=<filename without extension> 
# 		2) make clean 
# 		3) make veryclean PROJECT=<filename without extension>
#       Set the PROJECT variable name (ex: PROJECT=Untitled) in the Makefile to
#       avoid typing PROJECT=<filename without extension> to the make command
#
PROJECT=example
TEMPDIR=.texpadtmp
PDFLATEX_FLAGS=-file-line-error -interaction=nonstopmode -synctex=1 -shell-escape -output-directory=$(TEMPDIR) 

all: compile

compile: 
	@mkdir -p $(TEMPDIR)
	@pdflatex $(PDFLATEX_FLAGS) $(PROJECT).tex
	@cp $(TEMPDIR)/$(PROJECT).log .
	@mv $(TEMPDIR)/$(PROJECT).pdf .

.PHONY: compile

clean:
	@rm -rf $(TEMPDIR)

.PHONY: clean

veryclean: clean
	@rm $(PROJECT).pdf

.PHONY: veryclean
