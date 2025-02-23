plan:
	therion wip-plan.thconfig
	#xdg-open out/wip.pdf

ee:
	therion wip-ee.thconfig
	xdg-open out/wip.pdf

print:
	therion outline-plan.thconfig
	therion outline-ee.thconfig
	therion print.thconfig
	
	cd src/print && pdflatex -output-directory=../../out/ print_with_outlines.tex
	xdg-open out/print_with_outlines.pdf

display:
	therion display.thconfig
	xdg-open out/display_2x4.pdf

wprint:
	cd src/print && pdflatex -output-directory=../../out/ print2.tex
	xdg-open out/print2.pdf

stage01:
	therion stage01.thconfig
	xdg-open out/new_park_stage_01_yellow.pdf

stage02:
	therion stage02.thconfig
	xdg-open out/new_park_stage_02_yellow.pdf

stage03:
	therion stage03.thconfig
	xdg-open out/new_park_stage_03_yellow.pdf

stage04:
	therion stage04.thconfig
	xdg-open out/new_park_stage_04_yellow.pdf

stage05:
	therion stage05.thconfig
	xdg-open out/new_park_stage_05_yellow.pdf


all:
	therion stage01.thconfig
	therion stage02.thconfig
	therion stage03.thconfig
	therion stage04.thconfig
	therion stage05.thconfig
	therion print.thconfig


