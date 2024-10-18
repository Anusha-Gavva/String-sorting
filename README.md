# String-sorting
str1="which is better python 2 or python 3"
out=str1.split()
d1={}
for i in out:
    d1[i]=out.count(i)
out1=sorted(d1.items())
for i,j in out1:
    print((i,j))
