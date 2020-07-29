# Q1.Use the Dictonary and make new Dictionary in which keys become values and values become keys.


```python
port1={21:"FTP",22:"SSH",23:"telnet",80:"http"}
port2={}
for key, values in port1.items():
    port2[values]=key
print("The New Dictionary in which keys are values and values are keys:", port2)
```

    The New Dictionary in which keys are values and values are keys: {'FTP': 21, 'SSH': 22, 'telnet': 23, 'http': 80}
    

# Q2.Take a list of tuple. Make new List which Contains sum of numbers of tuples.


```python
l=[(1,2),(3,4),(5,6),(4,5)]
L1=[]
for i in range(len(l)):
    L1.append(sum(l[i]))
print("The New List contains the sum of Numbers of tuples are:", L1)
```

    The New List contains the sum of Numbers of tuples are: [3, 7, 11, 9]
    

# Q3. Take a list as shown Below. The List contains tuples and Lists. Make the elements of inner lists and tuples to outer list.


```python
l=[(1,2,3),[1,2],["a","hit","less"]]
print("The new List is :",[j for i in range(len(l)) for j in l[i]])
```

    The new List is : [1, 2, 3, 1, 2, 'a', 'hit', 'less']
    
