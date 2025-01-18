# RentCalculator
#Below is the code for the code of rent calculator , copy the code to run it, hope you leave a good comment after using the program code

#necessary details needed for calculation of rent
rent = int(input("Enter your hostel/flat rent = "))
food = int(input("Enter the amount of food ordered = "))
electricity = int(input("Enter the total of electricity spent = "))
persons = int(input("Enter the number of persons living in room/flat = "))

#calculation for amount of money every person needs to pay

output=(food+rent+electricity)/persons

print("Each person will pay =" ,output)
