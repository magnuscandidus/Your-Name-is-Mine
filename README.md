# Your-Name-is-Mine
def subseq(a,b):

# Boolean valued function that takes two strings as input and returns True if+

# the first string is subsequence of second string, otherwise False.

    n1 = len(a)

    n2 = len(b)

    i=0

    j=0

    

    while i<n1 and j<n2:

        if a[i]==b[j]:

            i+=1 

            j+=1 

        else:

            j+=1 

    if i==n1:

        return "YES" 

    else:

        return "NO"

    

for _ in range(int(input())):

    w,m = map(str, input().split())

    

    if len(m)>len(w):

        print(subseq(w,m))

    else:

        print(subseq(m,w))





        

        
