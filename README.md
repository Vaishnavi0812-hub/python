# def max_num(num1,num2,num3):
#     if num1>=num2 and num1>=num3:
#         return num1
#     elif num2>=num1 and num2>=num3:
#         return num2
#     else:
#         return num3
    
# print(max_num(3,40,5))

# num1=float(input("Enter first no:"))
# op=input("Enter operator:")
# num2=float(input("Enter second no:"))

# if op== "+":
#     print(num1+num2)
# elif op== "-":
#     print(num1-num2)
# elif op=="*":
#     print(num1*num2)
# else:
#     print("invalid")

# monthConversions= { "Jan": "January", "Feb": "February" , "Mar" : "March"}
# print(monthConversions["Feb"])

# i=1
# while i<=10:
#     print(i)
#     i=i+1

# print("Done")

# secret_word= "Giraffe"
# guess=""
# guess_count=0
# guess_limit=3
# outofguesses= False

# while guess!= secret_word and not(outofguesses):
#     if guess_count< guess_limit:
#        guess= input("Enter guess:")
#        guess_count=guess_count+1
#     else:
#         outofguesses= True

# if outofguesses:
#     print("Wrong")
# else:
#     print("Correct")

# for letter in "Giraffe Academy":
#     print(letter)
# for i in range(3,10):
#     print(i)

# for i in range(5):
#     if i==0:
#         print("First")
#     else:
#         print("not first")
# def power(base_num, power_num):
#     result=1
#     for index in range(power_num):
#         result=result*base_num

#     return result
# print(power(3,2))

# my_list=[ [1,2,3],
#           [4,5,6], 
#           [7,8,9], 
#           [0] ]
# print(my_list[2][1])

# for row in my_list:
#     for col in row:
#         print(col)

# def translate(phrase):
#     translation=""
#     for letter in phrase:
#         if letter in "AEIOUaeiou":
#             if letter.isupper():
#                 translation=translation + "G"
#             else:
#                 translation=translation+ "g"
#         else:
#             translation=translation + letter

#     return translation

# print(translate(input("Enter a phrase:")))
# try:
#     value=10/0
#     num=int(input("Enter a number:"))
#     print(num)
# except ZeroDivisionError:
#     print("Divided by zero")
# except ValueError:
#     print("Invalid")

# employee_file= open("Employee.data1.py", "w")
# employee_file.write("\n Vaish- Digital Marketer")
# employee_file.close()

# class Student:

#     def __init__(self, name, major, gpa, is_on_probation):
#         self.name= name
#         self.major=major
#         self.gpa=gpa
#         self.is_on_probation=is_on_probation

#     def on_honour(self):
#         if self.gpa>=3.5:
#             return True
#         else:
#             return False

# from Studentdata import Student

# student1= Student("Alex", "Business", 4.0, False)
# student2= Student("Josh", "Medicine", 3.8, False)
# print(student1.on_honour())

# class Chef:

#     def make_chicken(self):
#         print("chef makes chicken")

#     def make_salad(self):
#         print("chef makes salad")

#     def make_specialdish(self):
#         print("chef makes special dish")

# from Chef import Chef

# mychef= Chef()
# mychef.make_chicken()



