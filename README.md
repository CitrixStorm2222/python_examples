# python_examples
correctchoice=0
classesprovided = ["Comp-Sci", "Biology", "Math", "History", "Spanish", "English", "P.E"]
print("Welcome to class picker.")
classchoice = input("What class would you like to take next year?")

for i in range(len(classesprovided)):
	if classesprovided[i] == classchoice:
		print("You can take that class!")
		correctchoice = 1
if correctchoice == 0:
    print("Sorry, that class is not avaliable!")

  
  
