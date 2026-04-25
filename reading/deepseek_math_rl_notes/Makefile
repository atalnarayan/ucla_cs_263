.PHONY: all clean

all: deepseek_math_rl_notes.pdf

deepseek_math_rl_notes.pdf: deepseek_math_rl_notes.tex
	latexmk -pdf deepseek_math_rl_notes.tex

clean:
	latexmk -C