# simple_dict_programs
#displaying the dict with single input
d={}
n=int(input())
for i in range(1,n+1):
  d[i]=i+1
print(d)

# print the odd num key with value multiply with 10
d={}
n=int(input())
for i in range(1,n+1):
  if i%2!=0:
    d[i]=i*10
print(d)
