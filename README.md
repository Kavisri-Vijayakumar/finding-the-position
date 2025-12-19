# finding-the-position
l=[2,12,123,456,78,12,599,9999,878954]
n=int(input("enter the number to be searched : "))
found = 0
for x in l:
  if x==n:
    print("item found at position : ",l.index(n)+i)
    found=1
if found==0:
  print("item not found")


enter the number to be searched : 9999
item found at position :  12



