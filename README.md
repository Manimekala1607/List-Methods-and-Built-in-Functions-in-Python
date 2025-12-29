# List-Methods-and-Built-in-Functions-in-Python
numbers = [10, 20, 30, 40, 50]
print("original list:", numbers)

numbers.append(60)
print("after append(60):", numbers)

numbers.insert(1, 15)
print("after insert(1,15):", numbers)

numbers.remove(30)
print("after remove(30):", numbers)

numbers.pop(2)
print("after pop(2):", numbers)

numbers.extend([70, 80])
print("after extend([70,80]):", numbers)

print("count of 20:", numbers.count(20))
print("index of 50:", numbers.index(50))

numbers.sort()
print("after sort():", numbers)

numbers.reverse()
print("after reverse():", numbers)

copy_list = numbers.copy()
print("copied list:", copy_list)

print("length of list:", len(numbers))
print("maximum value:", max(numbers))
print("Minimum value:", min(numbers))
print("Sum of list:", sum(numbers))

numbers.clear()
print("After clear():", numbers)

OUTPUT:
original list: [10, 20, 30, 40, 50]
after append(60): [10, 20, 30, 40, 50, 60]
after insert(1,15): [10, 15, 20, 30, 40, 50, 60]
after remove(30): [10, 15, 20, 40, 50, 60]
after pop(2): [10, 15, 40, 50, 60]
after extend([70,80]): [10, 15, 40, 50, 60, 70, 80]
count of 20: 0
index of 50: 3
after sort(): [10, 15, 40, 50, 60, 70, 80]
after reverse(): [80, 70, 60, 50, 40, 15, 10]
copied list: [80, 70, 60, 50, 40, 15, 10]
length of list: 7
maximum value: 80
Minimum value: 10
Sum of list: 325
After clear(): []

