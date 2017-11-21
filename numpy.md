### 文件1

```python
numpy.genfromtxt("world_alcohol.txt", delimiter=",", dtype = str)


print(help(numpy.genfromtxt)) #帮助文档

vector = numpy.array([5, 10, 15, 20])    #相同类型
matrix = numpy.array([[5, 10, 15], [20, 25, 30], [35, 40, 45]])

print(vector.shape) #(4,)

#When NumPy can't convert a value to a numeric data type like float or integer,
#it uses a special nan value that stands for Not a Number

#读取文件
world_alcohol = numpy.genfromtxt("world_alcohol.txt", delimiter=",", dtype="U75", skip_header=1)

#切片
matrix = numpy.array([
                    [5, 10, 15], 
                    [20, 25, 30],
                    [35, 40, 45]
                 ])
print(matrix[:,0:2])
```



### 文件2

```python

```

