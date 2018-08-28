# CodeGuidelines

## Richard Powell's Code Guidelines

1. Don’t sweat the small stuff.
2. Compile cleanly at high warning levels.
3. Have your changes code reviewed.
4. Don’t write surprising code.
5. Try to have your class/function do one thing, and one thing well.
6. Correctness, simplicity, and clarity come first.
7. No globals.
8. Encapsulate and Hide information.
9. Never use `friend` — it isn't.
10. Use explicit RAII and Smart Pointers.
	- If you have to manage a resource, make a class.
	- If you have to write a dtor, you’re doing it wrong.
11. Never write new and delete.
12. Prefer Errors in this order: Compile Time > Link Time > Run Time
13. Always `auto` (almost).
14. Use `const` always.
15. No Macros.
16. Declare variables as locally as possible, preferably only when used.
17. Short functions.
18. Prefer your functions as far as left as possible (no deep nesting).
19. Make headers self-sufficient.
20. Inheritance is the base class of all evil — prefer composition to inheritance.
21. Provide abstract interfaces.
22. Always use `override`.
23. Avoid Implicit conversions.
24. Don’t provide pointers to internals — never provide `GetHandle()`.
25. Prefer free functions.
26. Consider using namespaces.
27. Avoid coding to a type, use templates to write Algorithms.
28. No naked `for` loops.
29. Use `assert` to document and test.
30. Write error-safe code.
31. Prefer exceptions to return error codes.
32. Use `vector`.  If you can’t, rewrite your code so you can use `vector`.
33. Don’t use c-style casts.  Use c++ style casts.  It’s ugly for a reason.
34. Consider variant over union.
35. Never use varargs, use variadic templates,
