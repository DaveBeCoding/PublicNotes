<h2 align="center">
    <strong>CODE QUICK TIP's</strong>
</h2>

<p> 								
<strong>Python</strong>
</p>

```python
Instead of directly manipulating the __doc__ property, the strategic placement of the string literal directly below the object will automatically set the __doc__ value:

EXAMPLE ->
    def print_greeting(name):
    """A simple function that says hello... [name..]"""
    print(f"Hello {name}, is it me you're looking for?")

OUTPUT -> {interactive mode}
    >>>help(print_greeting)
Help on function print_greeting in module __main__:

print_greeting(name)
    A simple function that says hello... [name..]
```

```console
View PyDoc module, and key uses
```

```python
python -m pydoc [name...] <- Documentation for the documentation

help([name]) -> interactive mode -> console

[name] does not need to be imported to see doc
```

<h3>Larger module, function description</h3>
```python

"""This is the summary line

This is the further elaboration of the docstring. Within this section,
you can elaborate further on details as appropriate for the situation.
Notice that the summary and the elaboration is separated by a blank new
line.
"""

# Notice the blank line above. Code should continue on this line.

````
<hr>

<p>
<strong>JavaScript</strong>
</p>

```console
stage document
````

```javascript
stage section
```

<hr>
<p> 								
<strong>C++</strong>
</p>

```c++
stage section
```

```console
stage document
```
