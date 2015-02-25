# exercise1
import math
def fill_tetrahedron(num):
	int(float(num))
	capacity=math.sqrt(2.0)*(num**3)*0.001/12.0
	print "The amount of water that can be filled in the tetrahedron is %.2f L" % capacity
dimension=raw_input("Input the length of the side of a regular tetrahedron: ")
dimension= int(float(dimension))
fill_tetrahedron(dimension)
