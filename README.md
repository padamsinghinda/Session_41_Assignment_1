# Session_41_Assignment_1
Scala Programming

1. 
list.count(x => x.length == 4)
list.count(_.length == 4)

2.
list.map(s => (s.length))

extra (Not required) :
list.map(s => (s, s.length))

3.
list.map(s => s.count(_ == 'm')).count(s => s != 0)

4.
list.map(s => s(0) == 'a').count(s => s == true)

