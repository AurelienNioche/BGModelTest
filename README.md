# BGModelTest
Simple tasks for testing the basal ganglia model from Topalidou et al. (2015).

---

	python3 setup.py install --user
	cp build/lib.macosx-10.9-x86_64-3.9/cdana/cdana.cpython-39-darwin.so cdana

Square, Triangle, ...

0110  < COG

0100   1    Top
0010   1    Bottom
0000   0    Left
0000   0    Right

 ^     ^ 
 ASS  MOT
 
Input: COG + ASS + MOT (simulate one "cortex" each time)
Output: action (top, bottom, left, right)