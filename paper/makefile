all:	full

once:
	pdflatex -halt-on-error template;

silent:
	pdflatex -halt-on-error template > /dev/null ; pdflatex -halt-on-error template > /dev/null ; open template.pdf > /dev/null

full:
	pdflatex -halt-on-error template; pdflatex -halt-on-error template; open template.pdf

clean:
	rm *.log *.nlo *.idx template.synctex* *.aux *.toc *.out
