docker-compose-script:
	latexmk -pdf -output-directory=/temp/ main_lab1.tex -jobname=YITPiIM.PO4.190333-01_81_00
	latexmk -pdf -output-directory=/temp/ main_lab2.tex -jobname=YITPiIM.PO4.190333-02_81_00
	latexmk -pdf -output-directory=/temp/ main_lab3.tex -jobname=YITPiIM.PO4.190333-03_81_00
	latexmk -pdf -output-directory=/temp/ main_lab4.tex -jobname=YITPiIM.PO4.190333-04_81_00
	latexmk -pdf -output-directory=/temp/ main_lab5.tex -jobname=YITPiIM.PO4.190333-05_81_00

	cp /temp/*.pdf /build/
