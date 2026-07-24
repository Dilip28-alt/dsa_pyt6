#O(n^3)
n=int(input("enter a number:"))
for i in range(n):
    for j in range(n):
        for k in range(n):
            print(i,end=" ")
        print()
    print()
