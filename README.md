# Take-input-from-user-and-check-wither-it-is-straight-line-or-not-using-python
x1=input('Enter x1: ')
x2=input('Enter x2: ')
x3=input('Enter x3: ')
x4=input('Enter x4: ')
y1=input('Enter y1: ')
y2=input('Enter y2: ')
y3=input('Enter y3: ')
y4=input('Enter y4: ')
m1=int(y2)-int(y1)/int(x2)-int(x1)
print('Slope 1',m1)
m2=int(y3)-int(y2)/int(x3)-int(x2)
print('Slope 2',m2)
m3=int(y4)-int(y3)/int(x4)-int(x3)
print('Slope 3',m3)
if m1==m2==m3:
    print('Straight line ')
else:
    print('Not straight line')
