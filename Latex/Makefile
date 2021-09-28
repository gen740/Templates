
project_name = document

run: build
	open $(project_name).pdf

build:
	lualatex $(project_name).tex

clean:
	rm -rf ./*.pdf ./*.log ./*.aux
