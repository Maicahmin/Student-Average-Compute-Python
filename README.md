# Student-Average-Compute-Python

About
A program that will compute for the students average. If the average is equal and above 75 status is Passed else You Failed the semester
    name = input("name: ")

    math = int(input("enter your math grade: "))

    science = int(input("enter your science grade: "))

    english = int(input("enter your english grade: "))


    sum = math + science + english

    average = float((sum/3))


    print("\nName: " + name)

    print("Math: " + str(math))

    print("Science: " + str(science))
    
    print("English: " + str(english))

    print("Average: " + str(average))


    if average >= 75:

    print("\nConggrats! you passed the semester :D ")
    
    if math < 75:
    
        print("But you need to retake math")
        
    elif science < 75:
    
        print("But you need to retake science")
        
    elif english < 75:
    
        print("But you need to retake english")
        
    else:

    print("\nSorry! you failed the semester :(")
