FORTHON=Forthon
PYTHON=python

example2: example2.F example2.v
	$(FORTHON) --nowritemodules example2
	mv build/*/*/*.so .
	$(PYTHON) example2.py

clean:
	rm -rf build example2py.so
