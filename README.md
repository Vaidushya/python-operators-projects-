#storing values
tree1 = 98
tree2 = 83
tree3 = 53
tree4 = 45
tree5 = 11

#doing sum
sum = tree1+tree2+tree3+tree4+tree5
print('Sum of all 5 trees is: ', sum)

#finding average
avg = sum/5
print('Average of all 5 trees is: ', avg)

#new work
#Taking amount for withdraw from user
amount = int(input('Please enter Amount for Withdraw : '))


#Calculating different type of notes
note_1 = amount//100
note_2 = (amount%100)//500
note_3 = ((amount%100)%500)//10

print('Notes of 100 rupees : ' , note_1)
print('Notes of 50 rupees : ' , note_2)
print('Notes of 10 rupees : ' , note_3)

#new work
#Take marks as input from the user
print('Enter Marks obtained in 4 subjects ')
Maths = int(input('Maths : '))
English = int(input('English : '))
Science = int(input('Science : '))
Hindi = int(input('Hindi : '))

#Calculating the percentage of marks
sum = Maths+English+Science+Hindi
print('sum of all 4 subjects')

percentage = (sum/400)*100

print(end = 'percentage mark = ')
print(percentage)

#new work
print('Enter number of days: ')
num = int(input())

year = int(num/365)
week = int(num%365)/7
day = int(num%365)%7

print("Total Number of Year(s): ")
print(year)
print("Total Number of Week(s): ")
print(week)
print("Total Number of Day(s): ")
print(day)
