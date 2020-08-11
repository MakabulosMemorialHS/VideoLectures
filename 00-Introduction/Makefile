.PHONY: clean slides jpeg

clean :
	rm *.log *.aux *.nav *.out *.snm *.toc
	rm 00-introduction.pdf

slides :
	pdflatex 00-introduction.tex

jpeg :
	pdftoppm 00-introduction.pdf 00-introduction -jpeg -rx 120 -ry 120
	mv 00-introduction-*.jpg Slide-Images/


