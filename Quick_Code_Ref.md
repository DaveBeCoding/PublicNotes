<h2 align="center">
    <strong>CODE QUICK TIP's</strong>
</h2>

<p> 								
<strong>Keyboard key names</strong>
    
 `	Acute, back quote, grave, grave accent, left quote, open quote, or a push.
    
 (	Open or left parenthesis.
    
 {	Open brace, squiggly brackets, or curly bracket.
 
 
</p>



<p> 								
<strong>Python</strong>
 ```python
    node.compute(*node.inputs) # * -> n-inputs unknown
 ```
    
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

<h3>Simple class skeleton</h3>

```python 
class Person:
    def __init__(self, name):
        self.name = name

    def say_hi(self):
        print('Hello, my name is', self.name)

    def main():
        p1 = Person("john")
        p1.say_hi()


if __name__ == '__main__':
    Person.main()

```

<h2>
Create Virtual Envirement
</h2>

```python

# Step 1

python -m venv /location/of/dir

# Step 2

source example_env/bin/activate

# Exit Venv

deactivate

```

```python
from <module> import <function1>, <function2>, ...

# exmaple

from os import listdir, system
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

<strong>React</strong>

</p>

<h3>Component(s) Passing Props</h3>

```javascript
import React from "react";
import Child from "./Child";

const Parent = () => {
  const data = "Hello Everyone";
  return (
    <div>
      <Child data={data} />
    </div>
  );
};

export default Parent;
```

<h3>Pass Props to child</h3>

```javascript
import React from "react";

const Child = (props) => {
  return <h2> {props.data} </h2>;
};

export default Child;
```

<h3>Using component(s) in App.js</h3>

```javascript
import React from "react";
import "./index.css";
import Parent from "./Parent";

const App = () => {
  return (
    <div className="App">
      <Parent />
    </div>
  );
};

export default App;
```

<h3>DOM Display</h3>

![](images/sampleOutputReact.png)

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
        <li class="item">Patch numbers change when a new build of the software is released to customers. This is normally for small bug-fixes or the like. </li></ul>
       <br><p>Other variations use build numbers as an additional identifier. So you may have a large number for X.Y.Z.build if you have many revisions that are tested between releases. I use a couple of packages that are identified by year/month or year/release. Thus, a release in the month of September of 2010 might be 2010.9 or 2010.3 for the 3rd release of this year.

There are many variants to versioning. It all boils down to personal preference.

For the "1.3v1.1", that may be two different internal products, something that would be a shared library / codebase that is rev'd differently from the main product; that may indicate version 1.3 for the main product, and version 1.1 of the internal library / package.</p>

</div>
</p>

```c++
stage section [versions]
```

```console
stage document [versions]
```

<hr>
<p>

<strong>Example Section</strong>

</p>

```javascript
stage section
```

```javascript
stage document
```

<hr>

<h3>TODO</h3>

```python
 update test-branch to main ::
 git fetch
 git rebase [main]

 history Display last n lines
 history [n n*] (start-n end-n*) -> first (n's)

 last [n n*]
 history [-n -n*] -> last (-n's)
```
