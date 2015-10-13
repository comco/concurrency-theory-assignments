assignment-lecture-10.pdf: assignment-lecture-10.tex
	pdflatex assignment-lecture-10.tex

Factory.til: Factory.psf
	psf -s Factory.psf

Factory.anim: Factory.til
	genanim -N -O -E Factory Factory.til

simulate: Factory.til Factory.anim
	tbsim Factory.til Factory.anim

clean:
	rm *.til
	rm *.anim
