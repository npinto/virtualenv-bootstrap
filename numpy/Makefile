
numpy: PV=numpy-1.6.1
numpy:
	test -f ${PV} || wget http://pypi.python.org/packages/source/n/numpy/${PV}.tar.gz
	tar xzf ${PV}.tar.gz
	cp -v site.cfg ${PV}
	cd ${PV} && python setup.py install
