# VIM Cheat Sheet  
A cheat sheet I have produced while learning how to use the almighty editor  
  
## Modes  
  
Esc - Normal Mode (default)  
i - Insert Mode  
(modifier)v - Visual mode  
  
## Navigation  
  
h - left  
j - down  
k - up  
l - right  
  
0 - go to the beginning of line  
$ - go to the end of line  
  
w - go to beginning to next word  
b - go to beginning of previous word  
e - go to end of next word  
  
{ - go to previous paragraph  
} - go to next paragraph  
  
% - go to matching parenthesis/bracket  
  
## Modifying text  
  
i - insert before current Char  
I - insert before current line  
a - append after current letter  
  
A - append at the end of current line  
o - insert starting at a new line after the current one  
  
r - replace current char with another  
  
## Deleting text  
  
x - delete current char  
  
dd - delete current line  
dw - delete a word starting from cursor  
  
d$ - delete everything until the end of line  
d0 - delete everything until beginning of line  
  
## Undo/Redo  
  
. (dot) - redo previously performed command  
u - undo previously performed command  
  
## Performing a command n times  
  
Every command can be performed several times by supplying it with a number  
  
e.g. **4iHello There\n** results in:  
> Hello There  
> Hello There  
> Hello There  
> Hello There  
  
Similarly, you can do the same for shortcuts such as [x, u, r...].  
The only exception is the d shortcut (delete).  
  
For it, you have to supply the number **after** the command. Also, you have to specify a direction for deleting by using the arrow keys.  
  
e.g. **d4(right)** will delete the next 4 characterx starting from the cursor.  
  
e.g. **d4$** will delete the next 4 lines.  
