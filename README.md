# tspython
My python patches

## str.split.patch
>>> 'qwertyuiopasdfghjkl'.split(5)
['qwert', 'yuiop', 'asdfg', 'hjkl']
>>> 'qwerty'.split(3)
['qwe', 'rty']
>>> 'qwerty'.split(5)
['qwert', 'y']
>>> 'qwerty'.split(2)
['qw', 'er', 'ty']

## list.split.patch
>>> a.split(3)
[[1, 2, 3], [4]]
>>> [1,2,3,4].split(2)
[[1, 2], [3, 4]]
>>> [1,2,3,4].split(10)
[[1, 2, 3, 4]]
