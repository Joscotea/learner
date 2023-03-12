# learner

Python 3.11.2 (tags/v3.11.2:878ead1, Feb  7 2023, 16:38:35) [MSC v.1934 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> print(false*True)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'false' is not defined. Did you mean: 'False'?
>>> print(False*True)
0
>>> print (bool(3.2))
True
>>> import numpy as np
>>> arr = np.random.normal(size = 5)
>>> print(array)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'array' is not defined
>>> print(arr)
[ 0.44374449  0.68242493 -1.46963235 -2.53188493  1.54328817]
>>> name= ["ada", "bolu", "kunle"]
>>> height= [1.9, 1.86, 1.92]
>>> students = [name, height]
>>> import matplotlib.pyplot as plt
>>> plt.plot (students[height], students[name])
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: list indices must be integers or slices, not list
>>> plt.plot (students["height"], students["name"])
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: list indices must be integers or slices, not str
>>> plt.plot (students[int(height)], students[int(name)])
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: int() argument must be a string, a bytes-like object or a real number, not 'list'
>>> plt.plot (height, name)
[<matplotlib.lines.Line2D object at 0x0000024F4E7ABA10>]
>>> plot.xlabel('height')
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'plot' is not defined. Did you mean: 'plt'?
>>> plt.xlabel('height')
Text(0.5, 0, 'height')
>>> plt.ylabel('name')
Text(0, 0.5, 'name')
>>> plt.show()
>>>
