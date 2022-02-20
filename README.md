# assignment2-20-02-22
prime numbers hackerrank
Q=int(input())
while(Q>0):
    X,Y=[int(X)for X in input().split()]
    sum=0
    for num in range(X+1,Y):
        c=0
        for i in range(1,1+num):
            if(num%i==0):
                c=c+1
        if(c==2):
            sum=sum+1
    Q=Q-1
    print(sum)
Input (stdin)
2
1 100
1 10000
Output (stdout)
25
1229
