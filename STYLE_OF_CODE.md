This file contains the conventions that will be used in every project. These will also apply to all sub-organizations and projects of Jappe Studios, unless otherwise specified in a specific repository or organization.

# C++
- **Enum entries** should be named with **uppercase snake case** identifiers; example: "ENUM_ENTRY".
- **Class, enum, struct, method, namespace** declarations should be named using **pascal case**; example: "MyClass".
- **Variables** should be named using **camel case**; example: "myVariable".
  - **Private** variables should always begin with **"m_"**, this does not apply for methods; example: "m_myVariable".
- Always avoid making unnecessary copies of objects.
- Always use the fast way of assigning variables in constructors, when possible. Like this: `MyClass(string someString) : m_someString(someString) {}`.

# Dart
- Use dart's linter packages' default conventions as much as possible.

# CSharp
- Use Microsoft's conventions.
