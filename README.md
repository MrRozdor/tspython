# tspython
My python patches

## str.split.patch
```python
>>> 'qwertyuiopasdfghjkl'.split(5)
['qwert', 'yuiop', 'asdfg', 'hjkl']
>>> 'qwerty'.split(3)
['qwe', 'rty']
>>> 'qwerty'.split(5)
['qwert', 'y']
>>> 'qwerty'.split(2)
['qw', 'er', 'ty']
```

## list.split.patch
```python
>>> a.split(3)
[[1, 2, 3], [4]]
>>> [1,2,3,4].split(2)
[[1, 2], [3, 4]]
>>> [1,2,3,4].split(10)
[[1, 2, 3, 4]]
```

## bin_oct_hex.patch
```python
>>> hex(42)
'2a'
>>> bin(42)
'101010'
>>> hex(10486)
'28f6'
```
