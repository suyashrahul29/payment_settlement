names = []
amounts = []
print("THIS PROGRAM SETTLES THE SPENDINGS WHEN DIFFERENT PEOPLE HAVE SPENT MONEY IN DIFFERENT AMOUNTS")
print("ENTER THE NAMES OF PEOPLE AND AMOIUNT SPENT BY THEM IN DESCENDING ORDER, THAT IS THE NAME AND AMOUNT OF THE PERSON WHO HAS SPENT THE MOST MONEY WILL BE ENTERED FIRST.")
print("------------------------------------------------------------------------")
n = int(input("ENTER THE NUMBER OF PEOPLE: "))
for i in range(n):
    names.append(input(f"ENTER THE NAME OF PERSON {i+1}: "))
    amounts.append(int(input(f"ENTER THE AMOUNT SPENT BY PERSON {i+1}: ")))
print("------------------------------------------------------------------------")
for i in range(n):
    amounts[i] = amounts[i]*-1
avg=abs(sum(amounts)/n)
for i in range (n-1):
    if (abs(amounts[n-i-1])<avg):
        diff1 = avg-abs(amounts[n-i-1])
        print(f"{names[n-i-1]} PAY {diff1} TO {names[0]}")
    if (abs(amounts[n-i-1])>avg):
        diff2 = abs(amounts[n-i-1])-avg
        print(f"{names[0]} PAY {diff2} TO {names[n-i-1]}")
