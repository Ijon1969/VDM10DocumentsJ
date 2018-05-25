# Much lazy

source=VDM10_lang_man

pdf:
	platex $(source).tex
	dvipdfm $(source) 2> ERR.out

clean:
	latexmk -c

clear:
	latexmk -C
