誰が要るのか知らないけれど
やってみるとちょっとおもしろい
論理演算のシンプルな実装です



論理和（AND)
```python
def AND(x, y):
    return bool(x and y)

print(AND(0,0))
print(AND(0,1))
print(AND(1,0))
print(AND(1,1))
```

否定論理和（NAND）
```python
def NAND(x, y):
    return bool(not x or not y)

print(NAND(0,0))
print(NAND(0,1))
print(NAND(1,0))
print(NAND(1,1))

#演算子がand →orに変化
```

論理和（OR）
```python
def OR(x, y):
    return bool(x or y)

print(OR(0,0))
print(OR(0,1))
print(OR(1,0))
print(OR(1,1))
```

否定論理和（NOR）
```python
def NOR(x, y):
    return bool(not x and not y)

print(NOR(0,0))
print(NOR(0,1))
print(NOR(1,0))
print(NOR(1,1))

#演算子がor →andに変化
```

排他的論理和（XOR）
```python
def XOR(x, y):
    return bool((x and not y) or (not x and y))

print(XOR(0,0))
print(XOR(0,1))
print(XOR(1,0))
print(XOR(1,1))
```

否定（NOT）
```python
def NOT(x):
    return bool(not x)

print(NOT(0))
print(NOT(1))
```
