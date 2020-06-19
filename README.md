# DEIDOS COVENANT

Deidos covenant is an algorithm to find all the solutions to a problem of "Sum of Subsets" that is NP-Complete, was developed by Oscar Riveros [oscar.riveros@peqnp.science] in 2012.

# Solutions

The algorithm out the explicit solution and/or complement, are "quivalents" or complementary.

# Build

	mkdir build
	cd build
	cmake -DCMAKE_BUILD_TYPE=Release ..
	make

# Usage
	
	./deidos_covenant instance.txt

# Format

The file format is: (use the gen_ssp.py to generate random examples) 

	python3 gen_ssp.py bits size

	SIZE
	TARGET
	N_1
	N_2
	...
	N_SIZE
