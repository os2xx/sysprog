# REV285 Mon 31 Jan 2022 22:35:40 WIB
# REV284 Fri 12 Mar 2021 07:29:51 WIB
# REV238 Sun 13 Sep 2020 11:18:18 WIB
# REV151 Thu 16 Aug 2018 22:40:32 WIB
# REV002 Mon 22 May 2017 09:37:31 WIB
# STARTX Tue 13 Sep 2016 09:30:20 WIB
# Adapted from Tobias Oetiker
###########################################################################

SHELL = /bin/bash
# Define some variables
# MAKEINDEX=makeindex
INCFILES=Makefile src/spII-jadwal.tex src/beamer.tex src/spHH.tex
PDFLATEX=pdflatex
PDFFILES= \
	sp00.pdf \
	sp01.pdf \
	sp02.pdf \
	sp03.pdf \
	sp04.pdf \
	sp05.pdf \
	sp06.pdf \
	sp07.pdf \
	sp08.pdf \
	sp09.pdf \
	sp10.pdf \


# The default targets
all: $(PDFFILES)

# 12 ######################################################################
sp00.pdf: src/sp00.tex ${INCFILES}
	-mkdir pdfbuild
	(TEXINPUTS=.:`pwd`/src:${TEXINPUTS:-:} && \
	 export TEXINPUTS && \
         cd pdfbuild && \
	 $(PDFLATEX) sp00 && \
	 $(PDFLATEX) sp00 && \
	 $(PDFLATEX) sp00 && \
	 mv sp00.pdf .. )
	 rm pdfbuild/*

# 12 ######################################################################
sp01.pdf: src/sp01.tex ${INCFILES}
	-mkdir pdfbuild
	(TEXINPUTS=.:`pwd`/src:${TEXINPUTS:-:} && \
	 export TEXINPUTS && \
         cd pdfbuild && \
	 $(PDFLATEX) sp01 && \
	 $(PDFLATEX) sp01 && \
	 $(PDFLATEX) sp01 && \
	 mv sp01.pdf .. )
	 rm pdfbuild/*

# 12 ######################################################################
sp02.pdf: src/sp02.tex ${INCFILES}
	-mkdir pdfbuild
	(TEXINPUTS=.:`pwd`/src:${TEXINPUTS:-:} && \
	 export TEXINPUTS && \
         cd pdfbuild && \
	 $(PDFLATEX) sp02 && \
	 $(PDFLATEX) sp02 && \
	 $(PDFLATEX) sp02 && \
	 mv sp02.pdf .. )
	 rm pdfbuild/*

# 12 ######################################################################
sp03.pdf: src/sp03.tex ${INCFILES}
	-mkdir pdfbuild
	(TEXINPUTS=.:`pwd`/src:${TEXINPUTS:-:} && \
	 export TEXINPUTS && \
         cd pdfbuild && \
	 $(PDFLATEX) sp03 && \
	 $(PDFLATEX) sp03 && \
	 $(PDFLATEX) sp03 && \
	 mv sp03.pdf .. )
	 rm pdfbuild/*

# 12 ######################################################################
sp04.pdf: src/sp04.tex ${INCFILES}
	-mkdir pdfbuild
	(TEXINPUTS=.:`pwd`/src:${TEXINPUTS:-:} && \
	 export TEXINPUTS && \
         cd pdfbuild && \
	 $(PDFLATEX) sp04 && \
	 $(PDFLATEX) sp04 && \
	 $(PDFLATEX) sp04 && \
	 mv sp04.pdf .. )
	 rm pdfbuild/*

# 12 ######################################################################
sp05.pdf: src/sp05.tex ${INCFILES}
	-mkdir pdfbuild
	(TEXINPUTS=.:`pwd`/src:${TEXINPUTS:-:} && \
	 export TEXINPUTS && \
         cd pdfbuild && \
	 $(PDFLATEX) sp05 && \
	 $(PDFLATEX) sp05 && \
	 $(PDFLATEX) sp05 && \
	 mv sp05.pdf .. )
	 rm pdfbuild/*

# 12 ######################################################################
sp06.pdf: src/sp06.tex ${INCFILES}
	-mkdir pdfbuild
	(TEXINPUTS=.:`pwd`/src:${TEXINPUTS:-:} && \
	 export TEXINPUTS && \
         cd pdfbuild && \
	 $(PDFLATEX) sp06 && \
	 $(PDFLATEX) sp06 && \
	 $(PDFLATEX) sp06 && \
	 mv sp06.pdf .. )
	 rm pdfbuild/*

# 12 ######################################################################
sp07.pdf: src/sp07.tex ${INCFILES}
	-mkdir pdfbuild
	(TEXINPUTS=.:`pwd`/src:${TEXINPUTS:-:} && \
	 export TEXINPUTS && \
         cd pdfbuild && \
	 $(PDFLATEX) sp07 && \
	 $(PDFLATEX) sp07 && \
	 $(PDFLATEX) sp07 && \
	 mv sp07.pdf .. )
	 rm pdfbuild/*

# 12 ######################################################################
sp08.pdf: src/sp08.tex ${INCFILES}
	-mkdir pdfbuild
	(TEXINPUTS=.:`pwd`/src:${TEXINPUTS:-:} && \
	 export TEXINPUTS && \
         cd pdfbuild && \
	 $(PDFLATEX) sp08 && \
	 $(PDFLATEX) sp08 && \
	 $(PDFLATEX) sp08 && \
	 mv sp08.pdf .. )
	 rm pdfbuild/*

# 12 ######################################################################
sp09.pdf: src/sp09.tex ${INCFILES}
	-mkdir pdfbuild
	(TEXINPUTS=.:`pwd`/src:${TEXINPUTS:-:} && \
	 export TEXINPUTS && \
         cd pdfbuild && \
	 $(PDFLATEX) sp09 && \
	 $(PDFLATEX) sp09 && \
	 $(PDFLATEX) sp09 && \
	 mv sp09.pdf .. )
	 rm pdfbuild/*

# 12 ######################################################################
sp10.pdf: src/sp10.tex ${INCFILES}
	-mkdir pdfbuild
	(TEXINPUTS=.:`pwd`/src:${TEXINPUTS:-:} && \
	 export TEXINPUTS && \
         cd pdfbuild && \
	 $(PDFLATEX) sp10 && \
	 $(PDFLATEX) sp10 && \
	 $(PDFLATEX) sp10 && \
	 mv sp10.pdf .. )
	 rm pdfbuild/*

# ## ######################################################################
cleanpdf: clean
	rm -f $(PDFFILES)

clean:
	rm -rf pdfbuild
	rm -f src/*.tex.bak

xfer:
	chmod 644 *.pdf  src/*
	cp sp??.pdf ~/tmp/
	cp check??.pdf ~/tmp/

