Factory.til: Factory.psf
	psf -s Factory.psf

Factory.anim: Factory.til
	genanim -N Factory Factory.til

simulate: Factory.til Factory.anim
	tbsim Factory.til Factory.anim

clean:
	rm *.til
	rm *.anim
