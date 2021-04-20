# Author: Dominik Harmim <harmim6@gmail.com>

PACK := 57_materialy.zip


.PHONY: pack
pack: $(PACK)

$(PACK): 57_nahled.png 57_pitchslide.png
	zip $@ $^


.PHONY: clean
clean:
	rm -f $(PACK)
