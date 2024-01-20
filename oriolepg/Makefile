all: configure build copy

configure:
	./configure.sh

build:
	rpmbuild -ba "./postgresql.spec"

copy:
	mkdir -p ./rpms
	find ~/rpmbuild -name '*.rpm' -exec cp {} rpms/ \;
