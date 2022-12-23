x = 'lionel messi', 'neymar', 'ronaldo', 'alvarez'
y = 'lewandoski', 'griezmann', 'aguero', 'pogba'
print(x)
print(y)
print(x+y)
# 6557
x = 'vjjoiigdgsgkh8khdgggskgguafsfs'
y = 'pogbshustabcjviossnviifskffsmfeof'
print(x.upper())
print(y.lower())
# 5641
mytuple = ("apple", "banana", "cherry")
myit = iter(mytuple)
print(next(myit))
print(next(myit))
print(next(myit))
print(mytuple[0])
print(mytuple[2])
print(mytuple[1])
# 767878


class MyNumbers:
    def __iter__(self):
        self.a = 1
        return self

    def __next__(self):
        if self.a <= 20:
            x = self.a
            self.a += 1
            return x
        else:
            raise StopIteration


myclass = MyNumbers()
myiter = iter(myclass)

for x in myiter:
    print(x)
