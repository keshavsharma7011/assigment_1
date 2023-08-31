# assigment_1
#question 1
r = int(input("enter radius of the circle : "))
area = 3.14*r*r
print("the arae of a circle of radius ",r,"is =",area)
#qustion 2
filename = input("Input the Filename: ")
fextns = filename.split(".")
print ("The extension of the file is : " , repr(fextns[-1]))
