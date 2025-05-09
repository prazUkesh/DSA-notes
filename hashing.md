# Hashing in Data Structute
- asing is a technique in DS that efficiently retrieves data in a way that allows for quick access

## components of Hashing
- key
- hash function
- hash table

> key
unique value inside a hash table that defines an index or location for storage of an item in a data structure
>
Hash Function
- K mod 10 (major)
- K mod 2 (major)
- Mid-square

Example
```
keys = 42,19,10,12, 28, 15, 26
no of keys = 7
1st Hash Function(k mod 10)
1st key = 42
42 mod 10 = 2 // 42 is stored in index 2

2nd hash function
k mod n (n-> no of keys)
19 mod 7 = 5
hash table => index => 0 to n-1

10 mod 7 = 3
12 mod 7 = 5 // collides
28 mod 7 = 0 // collides
15 mod 7 = 1 //collides
```
Example 2
```
keys: 123, 345, 612, 777
3rd hash function - mid square
1 st key = 123
 mid-value = '2'
 2^2 = 4

2nd key = 345,
mid-value = 4
4^4 =16

3rd index = 612,
mid value= 1
1^1=1

4th index, 777
mid-value = 7
7^7 = 49
 ```
## collision resolution techniques
- chaining (open hashing)
- open addressing (closed chaining)
  -   linear probing
  -   quadratic probing
  -   double hashing

```
keys: 41, 19, 10,12, 15

k mod n
n=5

index starts from 0 and goes upto (n-1)



```

### double hasing
```
h1(k) = k mod 11
h1(k) = 8 - (k mod 8)
h2(k)+ix(h2(k)) mod 11
```












