# Py_Clock

A simple digital clock using Python's tKinter module.

Tkinter is the standard GUI(<b>Graphical user interface</b>) library for Python. Python when combined with Tkinter provides a fast and easy way to create GUI applications. 
Tkinter provides a powerful object-oriented interface to the Tk GUI toolkit.

The <b>tkinter.ttk</b> module provides access to the Tk themed widget set, introduced in Tk 8.5. 
If Python has not been compiled against Tk 8.5, this module can still be accessed if Tile has been installed.

## The real difference between the two: 
Tkinter widgets are more configurable, and ttk is more modern and it is configurable with styles which are really handy shortcuts. <br>
And Tkinter is like the core of the window and ttk is styling.

## What is tkinter config?
config is used to access an object's attributes after its initialisation. <br>
For example, here --> label = Label(root, font=('ds-digital', 60), background = 'black', foreground = 'cyan')

## time module
Python has defined a module, “time” which allows us to handle various operations regarding time, its conversions and representations, 
which find its use in various applications in life. 
The beginning of time is started measuring from 1 January, 12:00 am, 1970 and this very time is termed as “<ins>epoch</ins>” in Python.


The <b>strftime()</b> function is used to convert date and time objects to their string representation. 
It takes one or more input of formatted code and returns the string representation. <br>
Syntax : strftime(format) <br>
Returns : It returns the string representation of the date or time object.
