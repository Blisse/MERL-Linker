#MERL Language Linker

This is a MERL file linker run by the following commands via the commandline.

	xxd -c 4 file1.merl > file1.xxd
	xxd -c 4 file2.merl > file2.xxd
	python linker.py file1.xxd file2.xxd output.txt

I need the xxd to slightly hack the inability for Python to read MERL files. It was a good learning experience for a bit of Python.

