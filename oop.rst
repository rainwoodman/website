C, Object Oriented Programming (OOP), and software design
---------------------------------------------------------

Most of these will become obsolete after computers are no longer state machines

`GObject <https://developer.gnome.org/gobject/stable/>`_ enables easier Object oriented Programming in C. 

`GLib <https://developer.gnome.org/glib/stable>`_ provides a core functionality library that the 
C programming language, were unable and unwilling to include into the standard library. Think of 'boost' of C++.

The Python Object system somewhat reassembles a crippled version of GObject system -- but everybody uses Python.

In my opinion, OOP is a way of thinking; it shall not be constrained by a specific computing language or tool.
Most of the time it is only a matter where to put the object pointer before or after the function name. 
In the end the computer sees neither objects nor classes; it sees instructions and pointers.

When the design becomes constrained by the tool of choice, think twice if there is over-engineering.

I feel that in a design treating tenary and higher order relations is usually the trickest.
I usually tend to follow the verbal hints -- write down a paragraph and see what is involved.
For more complicated system (e.g. Payroll) this may not work as well.

Some of the knowledgable discussions on `Cunningham & Cunningham, Inc <http://c2.com>`_ are very entertaining.

Computer languages evolve over time; the way people write also evolves. Javascript today is very different from
javascript in 2003. I have a feeling this applied to C++ too.
