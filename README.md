# Same-or-Not in python
n1 = int(input())
n2 = int(input())
f = True
f = n1==n2
s1 = 0
s2 = 0
for i in range(n1):
  h = int(input())
  s1 += h
for i in range(n2):
  h = int(input())
  s2 += h
f &= s1==s2
if f:
  print('Same')
else:
  print('Not Same')
