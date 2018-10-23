# palindrome
finding if the string is a palindrome or not
import sys
def is_palindrome(st):
    return(st==st[::-1]) 
print(is_palindrome(sys.argv[1]))  
