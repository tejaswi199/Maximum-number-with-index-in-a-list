#Approach-1
n=int(input())
a=list(map(int,input().split()))
print(a)
m=0
for i in a:
  if i>m:
    m=i
print(m,a.index(m))

#Approach-2
n=int(input())
a=list(map(int,input().split()))
print(a)
m=0
for i in range(n):
  if m<a[i]:
    m=a[i]
print(m,a.index(m))

#Approach-3
n=int(input())
a=list(map(int,input().split()))
print(a)
z=max(a)
print(z,a.index(z))
