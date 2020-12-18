all : P0 P1

P0 : rr.Rmd
	Rscript -e "library(rmarkdown); render('rr.Rmd', 'xaringan::moon_reader')"

P1 : Pres1.Rmd
	Rscript -e "library(rmarkdown); render('Pres1.Rmd', 'xaringan::moon_reader')"

P2 : phylogeneticTrees.Rmd
	Rscript -e "library(rmarkdown); render('phylogeneticTrees.Rmd', 'xaringan::moon_reader')"

clean :
	rm Lesson*html; rm -r *_cache
