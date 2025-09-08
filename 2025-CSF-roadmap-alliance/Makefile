build:
	#npx @marp-team/marp-cli@latest presentation.md \
	#	--html -o presentation.html --allow-local-files
	#npx @marp-team/marp-cli@latest presentation.md \
	#	--html -o presentation.pptx --allow-local-files
	npx @marp-team/marp-cli@latest presentation.md \
		--html -o presentation.pdf --allow-local-files

	npx @marp-team/marp-cli@latest presentation-en.md \
		--html -o presentation-en.pdf --allow-local-files

dev:
	npx @marp-team/marp-cli@latest -s -w \
		--allow-local-files --html .
