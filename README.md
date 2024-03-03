# palindrome
def is_paindrome(string):
    for i in range(len(string)):
        if string[i] != string [-i -1]:
            return False
    return True
            
s = input("Enter your string: ")
if is_paindrome(s):
    print("Is paindrome!")
else:
    print("Is not paindrome!")
