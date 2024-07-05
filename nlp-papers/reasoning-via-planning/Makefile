PROJECT=emnlp2023
TEX_ENGINE=xelatex

BUILDTEX=$(TEX_ENGINE) -shell-escape $(PROJECT).tex
REMOVE_AUXILIARY=make clean
PUBLISH_NOTES=make git-push

all:
	$(REMOVE_AUXILIARY)
	$(BUILDTEX)
	$(BUILDTEX)
	$(BUILDTEX)
	$(REMOVE_AUXILIARY)
	$(PUBLISH_NOTES)

clean-all:
	rm -rf *.aux *.log *.out $(PROJECT).pdf

clean:
	rm -rf *.aux *.log *.out

git-push:
	git add emnlp2023.pdf
	git commit -S -m "Update paper study notes - Attention is All You Need"
	git push origin master
