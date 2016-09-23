GIT_ROOT = $(shell git rev-parse --show-toplevel 2>/dev/null)

install:install_mindmapit

install_mindmapit:SRC=mindmapit
install_mindmapit:TARGET=$(GIT_ROOT)/mindmapit
install_mindmapit:
	mkdir -p $(TARGET)
	cp $(SRC)/index.html $(TARGET)
	cp -r $(SRC)/dist $(TARGET)
