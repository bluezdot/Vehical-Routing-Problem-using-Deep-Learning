# Project 1


## Project structure:

<p>projectname <br>
&emsp;├── MANIFEST.in<br>
&emsp;├── setup.py<br>
&emsp;├── README<br>
&emsp;├── .gitignore<br>
&emsp;├── .git<br>
&emsp;├── projectname_env<br>
&emsp;└── projectname<br>
&emsp; &emsp; ├── __init__.py<br>
&emsp; &emsp;    ├── subpackageone<br>
&emsp; &emsp;    │   ├── __init__.py<br>
&emsp; &emsp;    │   ├── second_module.py<br>
&emsp; &emsp;    │   ├── tests<br>
&emsp; &emsp;    │   │   └── test_second_module.py<br>
&emsp; &emsp;    │   └── models<br>
&emsp; &emsp;    │   &emsp;  └── model1<br>
&emsp; &emsp;    ├── first_module.py   <br>
&emsp; &emsp;    └── tests<br>
&emsp; &emsp;    &emsp; &emsp; └── test_second_module.py<br>
</p>



## Coding convention (Use Pep 8 for coding convention):

### Code Layout
#### Identation
- Use 1 tab ( ~ 4 spaces ) per indentation level.
- In case the length of a line is greater than 79, break the line and continue from the start of the same level component above.
- Break the line before operations.
- Separate the "def" and "class" with others by 2 empty lines. Separate method in a class by 1 empty line.
- Import 1 library in 1 line.
- Use space in "Pet Peeves" format
#### Comment
- Use block comment before a component.
- Use inline comment right after a line to explain it.
#### Naming Conventions
- Package and module name: Short, all-lowercase.
- Class and Exception name: CapWord.
- Function, method and variable name: Lowercase with underscores:
- Use one leading underscore only for non-public methods and instance variables.
- Constant: All capital letters with underscores separating words. <br>
source: https://www.python.org/dev/peps/pep-0008/.
