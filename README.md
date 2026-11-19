print("DMD Property Management\n")
print("Properties for rent\n")

name = input("What is your name?: ")

print("\nHello, " + name + "!\n")

#add email and phone number

city = input("What city are you looking in?: ")

# Knoxville Properties
apt1 = "308 Knox Rd Apt 1"
link1 = "PASTE ZILLOW LINK 1 HERE"

apt2 = "308 Knox Rd Apt 3"
link2 = "PASTE ZILLOW LINK 2 HERE"

apt3 = "724 Ben Hur"
link3 = "PASTE ZILLOW LINK 3 HERE"

# OakRidge Properties
apt4 = "363 Robertsville Rd"
link4 = "PASTE ZILLOW LINK 4 HERE"

apt5 = "167 Latimer Rd"
link5 = "PASTE ZILLOW LINK 5 HERE"


if city == "Knoxville":
    print("\nApartments in Knoxville:\n")
    print(apt1 + "\n" + link1 + "\n")
    print(apt2 + "\n" + link2 + "\n")
    print(apt3 + "\n" + link3 + "\n")

elif city == "Oakridge" :
    print("\nApartments in Oakridge:\n")
    print(apt4 + "\n" + link4 + "\n")
    print(apt5 + "\n" + link5 + "\n")

else:
    print("\nCity not found. Please try again.")

print("\nThank you " + name + " for choosing DMD Property Managements!")
