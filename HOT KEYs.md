<h2 align="center">
    <strong>UNI-HOTKEYs</strong>
</h2>

<p> 								
<strong>DESKTOP LINUX</strong>
</p>

```console
stage document
```

```javascript
Win + D	Show Desktop
Ctrl + C 	Copy any highlighted text, image, or some other object to the clipboard.
Ctrl + V 	Paste copied text, image, or some other object from the clipboard.
Ctrl + X 	Cut highlighted text, image, or some other object.
Ctrl + S 	Save the currently opened file.
Ctrl + N 	Create a new file.
Ctrl + Z 	Undo the last action.
Ctrl + Q 	Quit the application in focus.
Ctrl + Alt + F1 to F6 	Switch to a virtual console.
Ctrl + Alt + F7 	Switch to the first graphical terminal.
```

<hr>

<p> 								
<strong>BROWSER(s)</strong>
</p>

```console
stage document
```

```javascript
Open the previous page from your browsing history in the current tab	Alt + Left arrow

Open the next page from your browsing history in the current tab	Alt + Right arrow

Close the current tab	Ctrl + w or Ctrl + F4

Close the current window	Ctrl + Shift + w or Alt + F4
```
<hr>
<p> 								
<strong>Vim</strong>
</p>

<h3>Open file(s)</h3>

```console
    
vim /path/to/file1 /path/to/file2 /path/to/file3
      
```

<h3>Move across file(s)</h3>
    
```console
   
:n(ext)  # jumps to the next file
:prev    # jumps to the previous file    
    
```

<h3>Tabs file(s)</h3>

```console

vim -p /path/to/file1 /path/to/file2 /path/to/file3

```

<h3>New Tabs [normal mode ]</h3>

```console

:tabe [/path/to/file] (command-line command)

```

<h3>Split Window</h3>

```console

:sp[lit]   [/path/to/file]  # splits the window horizontally [and opens the file]
:vs[plit]  [/path/to/file]  # splits the window vertically [and opens the file]

```

<h3>Current Window(s) & Tab(s)</h3>

```console
:tabs

```

<h3>Current File</h3>

```console

:f

```
    
<hr>
<p> 								
<strong>System</strong>
</p>

<h3>SYNOPSIS</h3>

```console
1> The synopsis section usually gives some example use-cases. Sometimes sub-commands have different options, so several examples might be shown.

2> Brackets [] always denote optional switches, arguments, options, etc.

3> Yes, the pipe | means or, particularly when inside brackets or parenthesis.

4> Brackets in brackets just means that the second part is dependent on the first, and also itself optional. Some switches you can use on their own or add a value to them. Commas at the start of a bracket would indicate there can be multiple comma separated values.

5> They lean on Regex concepts, but are meant to be human readable so don't follow all the escaping rules etc.
```

<h3>SYNOPSIS Ref</h3>

```console

bold text -> type exactly as shown
italic text -> replace with [your] argument
[-abc] -> any or all arguments withion [ ] optional
-a | -b -> either || !both
arg ... -> repeatable
[expression] ... -> expression in [] repeatable

```
