# Program-to-find-minimum-and-maximum-number-form-a-list.
#-
#-
#this part will take input form the user and add it in the list


y=int(input("Enter the length of list = "))
t=[]
for i in range(0,y):
    x = int(input("Enter the number for list = "))
    t.append(x)

#this part will sort the list in ascending order


def max():
    global t
    t.sort()
    return t


x=max()  #now x have the user input list in ascending order as the first element of list is the smallest one
l=(x[::-1])   #and l have user input list in descending order as the first element of list is the greatest one
print("Minimum number form list is ",x[0])   #printing the smallest number
print("Maximum number from list is ",l[0])   #printint the greatest number
