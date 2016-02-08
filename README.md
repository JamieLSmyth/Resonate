# Resonate
An enhancement to the java Reflection library

## Slated to support the following features not found in the reflection library
* Better Generic/Type support (specificaly for concrete subclasses)
* Better method/constuctor matching
** allows better vararg matching (`[Integer.class, String.class, String.class]` will match `method(Integer x, String...args)`)
** allow var args to be ignored (`[String.class]` will match method(String value, Object...args))
* option to discard exceptions in exchange for Optionals when appropriate
