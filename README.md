# Jarvis
Just a Small Demo Program that is used to Suggest which Car to be Driven for your Trips
#Jarvis
day=int(input("Please Enter  Date: "))
month=int(input("Please Enter Month: "))
year=int(input("Please Enter Year: "))
time=float(input("Enter Time: "))
gender=input("Enter Gender: ")
if (time<12):
    print("Good Morning Mam!,I am Jarvis")
    print("Date: ",day,month,year,"Time: ",time)
elif (time>12 and time<19):
    print("Good Afternoon Mam!,I am Jarvis")
    print(day,month,year,time)
else:
    print("Good Evening Mam!, I am Jarvis")
    print(day,month,year,time)
choice=int(input("Enter your choice:"))
if(choice==1):
    print("Have Comfortness with Mercedez Benz")
elif (choice==2):
    print("Have a Drive with Porsche")
elif(choice==3):
    print("Have Fun with Audi")
else:
    print("Have a Luxury Drive  with Rolls Royce")
