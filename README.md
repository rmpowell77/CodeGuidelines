# CodeGuidelines

## Richard Powell's Code Guidelines

1 Don’t sweat the small stuff.
2 Compile cleanly at high warning levels.
3 Have your changes code reviewed.
4 Don’t write surprising code.
5 Try to have your class/function do one thing, and one thing well.
Correctness, simplicity, and clarity come first.
No globals.
Encapsulate and Hide information.
Never use `friend` — they aren’t worth it.
Use explicit RAII and Smart Pointers.
	- If you have to manage a resource, make a class.
	- If you have to write a dtor, you’re doing it wrong.
Never write new and delete.
Prefer Errors in this order: Compile Time > Link Time > Run Time
Always `auto` (almost).
Use 	`const` always.
No Macros.
Declare variables as locally as possible, preferably only when used.
Short functions.
Prefer your functions as far as left as possible (no deep nesting).
Make headers self-sufficient.
Inheritance is the base class of all evil — prefer composition to inheritance.
Provide abstract interfaces.
Always use `override`.
Avoid Implicit conversions.
Don’t provide pointers to internals — never provide `GetHandle()`.
Prefer free functions.
Consider using namespaces.
Avoid coding to a type, use templates to write Algorithms.
No naked `for` loops.
Use `assert` to document and test.
Write error-safe code.
Prefer exceptions to return error codes.
Use `vector`.  If you can’t, rewrite your code so you can use `vector`.
Don’t use c-style casts.  Use c++ style casts.  It’s ugly for a reason.
Consider variant over union.
Never use varargs, use variadic templates,
