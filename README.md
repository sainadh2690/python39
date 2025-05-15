'''write a program to find the entered character is a vowel or a consonent , while user input could be either upper or lower case using if - elif -else'''
ch = input("enter a char from a -> z")
if ch=='a' or ch=='e' or ch=='i' or ch=='0' or ch=='u':
    print(ch, "is a vowel")
elif ch=='A' or ch=='E' or ch=='I' or ch=='o' or ch=='U':
    print(ch, "is a vowel")
else:
    print(ch,"is a consonent")
