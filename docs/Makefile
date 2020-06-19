fonts : $(_assets/fonts/*) _scripts/encode_fonts.sh
	_scripts/encode_fonts.sh _assets/fonts/* > _sass/_fonts.scss

.PHONY: serve
serve:
	jekyll serve --host 0.0.0.0

.PHONY: clean
clean:
	rm -rf ./_site
