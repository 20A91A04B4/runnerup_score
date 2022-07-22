# runnerup_scoren = int(input())
n = int(input())
arr =list(map(int, input().split()))
m=[]
k=max(arr)
for i in arr:
    m.append(i)
    if i==k:
        m.remove(k)
print(max(m))
