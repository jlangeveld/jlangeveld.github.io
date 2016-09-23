GIT_ROOT = $(shell git rev-parse --show-toplevel 2>/dev/null)

translate:
	pandoc -so $(GIT_ROOT)/index.html $(GIT_ROOT)/src/index.md
