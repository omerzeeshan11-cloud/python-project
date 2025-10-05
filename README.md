# python-project
# Student Information & Marks Calculator

print("===== Student Information & Marks Calculator =====")

# Step 1: Take student details
name = input("Enter Student Name: ")
father = input("Enter Father's Name: ")
city = input("Enter City: ")

# Step 2: Take marks of 5 subjects
print("\nEnter marks out of 100:")

eng = int(input("English: "))
math = int(input("Math: "))
sci = int(input("Science: "))
comp = int(input("Computer: "))
urdu = int(input("Urdu: "))

# Step 3: Calculate total and percentage
total = eng + math + sci + comp + urdu
percentage = total / 5

# Step 4: Assign grade
if percentage >= 80:
    grade = "A+"
elif percentage >= 70:
    grade = "A"
elif percentage >= 60:
    grade = "B"
elif percentage >= 50:
    grade = "C"
else:
    grade = "Fail"

# Step 5: Display result
print("\n===== Student Report Card =====")
print(f"Name        : {name}")
print(f"Father Name : {father}")
print(f"City        : {city}")
print("------------------------------")
print(f"Total Marks : {total}/500")
print(f"Percentage  : {percentage:.2f}%")
print(f"Grade       : {grade}")
print("================================"
