# S51360
# Soalan 1
def  countSetBits(n): 
    count = 0
    while (n): 
        count += n & 1
        n >>= 1
    return count 
  

i = 24
print(countSetBits(i)) 
