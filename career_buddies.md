[Preparation](#preparation)
[IT Basics](#it-basics)
[IT more advanced topics](#it-more-advanced-topics)
[Programming Tasks](./programming_tasks.md)
[OOP - Object Oriented Programming](./oop.md)

##Preparation
- Install Linux of your choice (can be any, even Ubuntu), alternatively any Apple computer with macOS or hackintosh.
    - Why: this is an industry standard in programming and many tools will just not work on Windows
    - To get familiar with Linux you can temporarily use Cygwin - it will work for very basic things
- Install VSCode and a chosen language (Python, Ruby, JS, etc.) plugin (all free)
- Get familiar with terminal and the default shell (bash). In some future it will be almost necessary to switch to zsh, which has better features.
- Get familiar with package manager of your Linux (for Ubuntu it’s apt, for macOS it’s brew).
- If you don’t know it yet learn touchtyping, you can find some online tools to train. It takes about 2 weeks until you’ll get comfortable with it, initially it’s painful, but it’s definitely worth learning.

##IT Basics
1. Basics
    1. Systems: binary, decimal, hexadecimal and conversions
    2. Numbers memory representation, negative numbers, floats, array, matrix
    3. RGB encoding, CMYK
    4. General knowledge vocabulary (maths, physics)
    5. [Vocabulary](#vocabulary) (IT science)
    6. Kind of files (binary, text (ASCII))
    7. Types: string, integer, float/double (real numbers), boolean
    8. Security (public/private keys, hash)
    9. IT professions (programmer/dev, architect, PM, PO, devops, QA)
    10. Readable data files formats: XML, json, yaml
    11. Regular expressions
2. Tools
    1. Terminal (console)
    2. Linux commands (ls, cp, mv etc.), CLI
    3. Standard output redirection, pipes
    4. Text editors (VSCode, Sublime Text 3, Atom, Vim)
    5. Configuration files (properties, json, yaml)
    6. Package manager (homebrew)
    7. Source control systems (git, github, ssh keys), Source Tree
3. Software design
    1. Vocabulary
    2. Kinds of software (standalone, website, service etc.)
    3. Layers of software (backend, frontend, database, middleware, etc.)
    4. Kinds of services (REST, RESTful, graphQL, json-rpc)
4. Development methods
    1. Waterfall
    2. Agile (scrum)
    3. Kanban
    4. Tools (kanban board, Jira, Waffle)
5. Web design
    1. Vocabulary
    2. Tools
    3. HTML
    4. CSS
    5. JavaScript, jquery
    6. JS frameworks
6. Testing
    1. Vocabulary
    2. Tools: Selenium
7. Database
    1. Relational and others
    2. Tools (Postico for macOS)
    3. SQL
8. Programming
    1. Vocabulary
    2. General principles (libs, modules)
    3. Python
    4. JavaScript
    5. Dynamic vs static typing

######Vocabulary

1. General knowledge
    1. Units: Volt, Hertz
    2. square, power
    3. Function, inverse function, domain/codomain (input/output)
    4. function composition
    5. continuous function, discrete function
    6. vector, matrix
    7. state, state transition, state machine
    8. kilo/mega/giga/tera/peta
    9. decy/centy/mili/micro/nano
2. IT vocabulary
    1. binary, decimal, hexadecimal representations
    2. directory, file, path, extension, absolute and relative paths
    3. Home, current/working directory (.), parent directory (..)
    4. (plain) text file, binary file
    5. website, url, http protocol
    6. text editor (editor of text file)
    7. command prompt, cursor
    8. kinds of memory organisation: stack, heap, garbage collection
3. Software design
    1. web application, frontend, backend, middleware, client, server
    2. database, SQL
    3. service, microservices
    4. REST service, json, API
4. Web design:
    1. Html, css, tags
5. Testing:
    1. manual/automatic tests, blackbox test
    2. regression test, integration test, functional test, unit test
6. Programming basics:
    1. expression, function
    2. script
    3. keyword
    4. function arguments/parameters, function result
    5. side effects
    6. variable, constant, variable/argument type
    7. function body
    8. assignment operator
    9. types (integer, float, double, string, boolean)
7. Programming:
    1. compilator (compilation)
    2. languages (JavaScript, Python, Java, C, SQL)
    3. imperative/functional programming language
    4. algorithm, program complexity
    5. Turing machine, lambda calculus
    6. Artificial intelligence (AI)

Links:
https://en.wikipedia.org/wiki/Signed_number_representations
https://en.wikipedia.org/wiki/State_(computer_science)

Homework:

- Review bits, bytes, words
- https://en.wikipedia.org/wiki/Hexadecimal
- Negative numbers memory representation (two complement)
- http://ascii.cl/conversion.htm
- https://en.wikipedia.org/wiki/Integer_(computer_science)
- ASCII https://en.wikipedia.org/wiki/ASCII
- Unicode (UTF-8, UTF-16)
- Terminal: Redirecting (>, <, >>), pipelining (|) http://linuxcommand.org/lts0060.php

To read:

- Pipes, redirections https://askubuntu.com/questions/420981/how-do-i-save-terminal-output-to-a-file
- Aliases http://www.linfo.org/alias.html


Tasks:
- How to make #8822aa colour more red? How to make it half less saturated? How to make it gray with approximately same brightness? Calculate in memory only.
- Find some websites to test regular expressions (regexps). Learn basics: *, ., (), [], ^, $, $1, $2. Get familiar with sed command line tool. Test some regexps of your choice,
- Find some websites to test SQL queries with predefined set of tables. Learn basics: select, update, delete, drop, where, group by, order by, and, or, in (nested queries), join (inner, outer, left, right), count, maximum, minimum, sum (aggregation functions). Test some queries of your choice on the sites you found. What is one-to-many relationship? What is many-to-many relationship? What is: normalization, index, constraint, trigger, sequence, key, primary key, foreign key, cascade. What is ORM (object relational mapping).
- Find some websites to test basic programming expressions in Python
    - find some Python tutorial and test some expressions
- Get familar with git and github (mayby some youtube tutorial?). Create some repository (git init), add some files, commit, change files commit. Then read how to create a repository in github and push there.
- In what kind of memory are typically located: local variables, global variables, object (class instances), class variables, function parameters, counters


##IT more advanced topics
#####Algorithms
- Basic algorithms
    - getting the smallest element from a list
    - sorting a list (many various algorithms)
    - finding an element in binary tree
    - calculating length of a list (or string)
    - reverse a string (also array, list)
- Space and time complexity
    - Big O notation (Omega notation) - especially for time
    - Polynominal vs non-polynominal complexity
- Data types
    - Basic atomic data types: integer, boolean, character, string
    - Basic containers: array, list, map (aka hash, dictionary), tree
    - Kind of trees: binary tree, binary search tree, balanced trees
- Vocabulary
    - instruction
    - expression
    - iteration
    - recursion
    - function vs procedure
    - function vs method
    - OOP (object oriented programming)
    - class vs object (instance)
    - variables vs constants (immutable variables)
    - local, global variables, function parameters, variables scopes
    - member variable (instance variable), class variable
    - basic instructions/expressions (for, if, while)
    - hash function, hash value, hash map
