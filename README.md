P=next_prime(2^127-1)
M=89646952373925749567894332598989134553
n=123456
secret = Mod(M,P)^n
print secret
