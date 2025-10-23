# homework
21.10.25
1.
disc = b**2 - 4*a*c
if disc > 0:
x1 = (-b + disc**0.5) / (2*a)
x2 = (-b - disc**0.5) / (2*a)
x1; x2
if disc = 0:
x = (-b + disc**0.5) / (2*a)
x
if disc < 0:
  print("no solution")
2.
thislist = [1, 5, 3, 6, 3, 5, 7, 9]
thislist.reverse()
print(thislist)
3.
def change(lst): 
    n = len(lst)
    if n < 2:
        print("List is too short to change elements.")
        return
        lst[n-1] = lst[0]
        
    example_list = [1, 3, 5, 6, 7]

print (change(example_list))
4.
thislist = [1, 3, 5, 6, 7]
a = (len(thislist))

thislist.sort()
print(thislist)
thislist[-1]/a
5.
unclear
