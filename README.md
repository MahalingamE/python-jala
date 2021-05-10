# python-jala

#basics

#(1)
class Person:                                   #class
   def __init__(self, name, age):
     self.name = name
     self.age = age

   def myfunc(self):                            #method
     print("Hello my name is " + self.name)

 p1 = Person("John", 36)                        #object
 p1.myfunc()

#(2)
print('mahalingam') 

#(3)
#single line comment

   ''' multiple
    line
    comment'''
    
#(4)variables for different data types
number=25
number1=True
letters='string'
decimalnumbers=2.5
print(type(number))
print(type(number1))
print(type(letters))
print(type(decimalnumbers))

#(5)
def f():
   global s
   print(s)
   s = "Look for  Python Section"
   print(s)

s = "Python is great!"
f()
print(s)

#(6)
def main():
    print("mahalingam")

if __name__ == "__main__":
    main()
