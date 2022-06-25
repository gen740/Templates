
project_name = document

run: build
	open -a /Applications/LivePDFviewer.app $(project_name).pdf

build:
	lualatex $(project_name).tex

clean:
	rm -rf ./*.pdf ./*.log ./*.aux
