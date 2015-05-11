.PHONY: FORCE
all: FORCE
	$(MAKE) -C .. virtacoin_qt test_virtacoin_qt
clean: FORCE
	$(MAKE) -C .. virtacoin_qt_clean test_virtacoin_qt_clean
check: FORCE
	$(MAKE) -C .. test_virtacoin_qt_check
bitcoin-qt bitcoin-qt.exe: FORCE
	 $(MAKE) -C .. virtacoin_qt
