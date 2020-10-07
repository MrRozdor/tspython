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

## TODO
```python
{qwe: 5}

{POST: post, GET: get} = request

seconds * 60s * 60m * 24h
distance = 5h * 100kmph

s .= lower()
	a[5] .= attribute

mb_none ?= 'default'
	var.attr ?= 'default'
	var['foo'] ?= 'default'

5 if x
	default simple types else
```

???
```python
a, b = 5, 10
c = {a, b}
```
