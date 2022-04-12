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

```

<hr>

<p>
<strong>JavaScript</strong>
</p>

```console
stage document
```

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

<hr>
<h3>
<strong>Software Version(s) Update(s)</strong>
</h3>
<p>
<div>
    <ul id="first_set">
    <p>
        X.Y.Z, which generally corresponds to major.minor.patch:
    </p>
       <li class="item"> Major version numbers change whenever there is some significant change being introduced. For example, a large or potentially backward-incompatible change to a software package. </li>
       <li class="item"> Minor version numbers change when a new, minor feature is introduced or when a set of smaller features is rolled out. </li>
    </ul>
    <ul id="second_Set">
        Patch numbers change when a new build of the software is released to customers. This is normally for small bug-fixes or the like. </li>
       < class="item"><br><p>Other variations use build numbers as an additional identifier. So you may have a large number for X.Y.Z.build if you have many revisions that are tested between releases. I use a couple of packages that are identified by year/month or year/release. Thus, a release in the month of September of 2010 might be 2010.9 or 2010.3 for the 3rd release of this year.

There are many variants to versioning. It all boils down to personal preference.

For the "1.3v1.1", that may be two different internal products, something that would be a shared library / codebase that is rev'd differently from the main product; that may indicate version 1.3 for the main product, and version 1.1 of the internal library / package.</p>
</ul>
</div>
</p>

```c++
stage section [versions]
```

```console
stage document [versions]
```
