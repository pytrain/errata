Why do you need a trailing comma within a tuple, list, or dictionary?
```python

>>> single = (1)
>>> type(single)
<class 'int'>
>>> single_tuple = (1,)
>>> type(single_tuple)
<class 'tuple'>
```

```python

>>> a = [
...     'some',
...     'thing'
...     'weird'
... ]
>>> 
>>> a
['some', 'thingweird']
```

The need for using `autoreload` in the Jupyter Notebooks for modifications to modules that are modified so that IPython does not grab the cached version.  
* [Link](https://stackoverflow.com/questions/5364050/reloading-submodules-in-ipython)
* [Link](https://stackoverflow.com/questions/1907993/autoreload-of-modules-in-ipython)

Using `Shift+Tab` gives a different contextual help within a Jupyter Notebook. We've only known about `Tab` until now.

Retrieving doc strings from modules and functions is needed.

What is the benefit and purpose of `__name__` and the shebang? -> Better explanation needed.


```python
x = [1,2,3,[4.5,6.7,7.8]]

for item in x:
    #try:
    #    for subitem in item:
    #        print(subitem)
    #except:
    #    print(item)
    
    
    if type(item) is list:
        for subitem in range(len(item)):
            print(item[subitem])
    else:
        print(item)
```
