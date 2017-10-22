.PHONY: all

TEX:=$(wildcard *.tex)
PDF:=${TEX:%.tex=%.pdf}
TEXMK:=latexmk -lualatex

all: ${PDF}

%.pdf: %.tex
	${TEXMK} $<
