# cnt-vwls-str
def count_vow(S):     count=0     for i in S:         if i in 'aeiouAEIOU':             count+=1             return count s=input("enter a string:") num_vow=count_vow(s) print("number of vowels:",num_vow)
