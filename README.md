# SCL_3_beer
CHEME 5500 Lab 3: Practice with GitHub

99 bottles of beer on the wall, 99 bottles of beer, you take one down, pass it around, 98 bottles of beer on the wall. 
98 bottles of beer on the wall, 98 bottles of beer, you take one down, pass it around, 97 bottles of beer on the wall. 
97 bottles of beer on the wall, 97 bottles of beer, you take one down, pass it around, 96 bottles of beer on the wall. 
96 bottles of beer on the wall, 96 bottles of beer, you take one down, pass it around, 95 bottles of beer on the wall.
95 bottles of beer on the wall, 95 bottles of beer, you take one down, pass it around, 94 bottles of beer on the wall.  
94 bottles of beer on the wall, 94 bottles of beer, you take one down, pass it around, 93 bottles of beer on the wall. 
93 bottles of beer on the wall, 93 bottles of beer, you take one down, pass it around, 92 bottles of beer on the wall. 
92 bottles of beer on the wall, 92 bottles of beer, you take one down, pass it around, 91 bottles of beer on the wall. 

90 bottles of beer on the wall, 90 bottles of beer, you take one down, pass it around, 89 bottles of beer on the wall. 

88 bottles of beer on the wall, 88 bottles of beer, you take one down, pass it around, 87 bottles of beer on the wall. 

86 bottles of beer on the wall, 86 bottles of beer, you take one down, pass it around, 85 bottles of beer on the wall. 
n=90
for n in range(90,0):
	number=n; 
	numberminus1=n-1; 
	print(str(number)+" bottles of beer on the wall," + str(number) + " bottes of beer, you take one down, pass it around," + str(numberminus1) + " bottles of beer on the wall.")
	n=n-2; 