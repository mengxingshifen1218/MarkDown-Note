## python trick
### 问题1：一个list[2,6,3,7,2,1,2,4,3,2]有重复项，怎么返回一个dict，key是list中的num，value是num的index？

例如: 

```python
dict = {1:[5], 2:[0,4,6,9], 3:[2,8], 4:[7], 6:[1], 7:[3]}
```

### 问题2 怎么一行代码生成list？
```python
x = [x for x in range(10)]
```