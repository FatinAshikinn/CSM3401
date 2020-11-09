# CSM3401
def countBits( n): 
    if (n == 0): 
        return 0
    else: 
        return (n&1) + countBits(n>>1) 
n = int(input("Enter your input number : "))
print(countBits(n))


#question2 
wc = input
def mostchar(input):
    wc = Counter(input)
    s= max(wc.values())
    i =wc.values().index(s)
    print wc.items()
