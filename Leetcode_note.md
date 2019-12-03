1. '^' is binary XOR operator. When the two corresponding binary digits are different, the result is 1. For example: 0 ^ 0 = 0, 1 ^ 1 = 0, 0 ^ 1 = 1.

2. Use 'ord()' to find ASCII code for characters.

3. Use 'set' to get rid of duplicated values. For example: a = {1,1,2,3} --> a = {1,2,3}. Other operations: set.add() instead of .append.

4. Remember to use .count() to count the times a element shows up in an array. Use .sort() to sort an array.

5. a[::2] to extract the elements of list 'a' that have even indexes. a[::-1] to make a copy of list 'a' in reverse order.

6. {0:031b}.format(num) will transfer num to a binary number which has 31 bits with 0s as placeholders.

7. collections.deque(): A deque is a double-ended queue. It can be used to add or remove elements from both ends. (.popleft())

8. zip(): The purpose of zip() is to map the similar index of multiple containers so that they can be used just using as single entity.  Syntax: zip(*iterators)  
Example_1: name = ["Manjeet", "Nikhil", Shambhavi", "Astha"]  roll_no = [4, 1, 3, 2]  marks = [40, 50, 60, 70]  mapped = zip(name, roll_no, marks)  mapped = set(mapped)  --> {('Shambhavi', 3, 60), ('Astha', 2, 70), ('Manjeet', 4, 40), ('Nikhil', 1, 50)}  
Example_2: A = ["abcdef", "uvwxyz"] set(zip(*A)) --> {('e', 'y'), ('a', 'u'), ('f', 'z'), ('b', 'v'), ('c', 'w'), ('d', 'x')}  
Note: Set is an unordered data structure.
