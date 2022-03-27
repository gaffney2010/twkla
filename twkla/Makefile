build_html:
	cp source/style.css html; pandoc -r latex -s --mathjax --toc -o html/linalg.html source/linalg.tex --css style.css --metadata title="Linear Algebra for Those Who Know Linear Algebra"
build_pdf:
	pdflatex -output-directory pdf source/linalg.tex; pdflatex -output-directory pdf source/linalg.tex
build_all:
	make build_html; make build_pdf
