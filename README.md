my_list = []  

count=0

count1=0

sum=0

sum1=0

while True:

         

    if element > 0:

        my_list.append(element)

    else:

        break

n=int(input("Enter Number You want to print first Odd and Even Number"))

print(" ---------------First ",n," Odd Numbers---------------")

for i in my_list:

    if count==n:

        break

    else:

        if i%2==0:

            print(i)

            count+=1

            sum+=i

print("Sum of First ",n," Even number => ",sum)

print("\n")

print("---------------First ",n," Even Numbers---------------")

for j in my_list:

    if count1==n:

        break

    else:

        if j%2!=0:

            print(j)

            count1+=1

            sum1+=j

print("Sum of First ",n," Even number => ",sum1)

#print("The list you have entered is:", my_list)
