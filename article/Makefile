# Author: Dominik Harmim <harmim6@gmail.com>

PACK := 2021-ExcelFIT-StaticAnalysisAtomicityInfer.tgz


.PHONY: pack
pack: $(PACK)

$(PACK): images/ *.cls *.tex *.bib
	COPYFILE_DISABLE=1 tar -czf $@ $^


.PHONY: clean
clean:
	rm -f $(PACK)
