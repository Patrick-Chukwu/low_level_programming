In the example above, say_hello behaves like a function name, as in any programming language. This is called the target. The prerequisites or dependencies follow the target. For the sake of simplicity, we have not defined any prerequisites in this example. The command echo "Hello World" is called the recipe. The recipe uses prerequisites to make a target. The target, prerequisites, and recipes together make a rule.

- Going back to the example above, when make was executed, the entire command echo "Hello World" was displayed, followed by actual command output. We often don't want that. To suppress echoing the actual command, we need to start echo with @:

say_hello:
A
A
A
A
A
A

C
A
B


D
        @echo "Hello World"""

