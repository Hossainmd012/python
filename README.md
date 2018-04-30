# python
from collections import Counter
a = [int(x) for x in input("Input a list: ").split()]
cnt=Counter(a)
d = {int(k):int(v) for k,v in cnt.items()}
k=list(d.keys())
k.sort()
print(k)
print(k[-2])
