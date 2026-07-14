# AI Developer Bootcamp

## Day 1

### What I learned today

- The terminal is like walking through rooms in a house.
- 'pwd' tells me where I am.
- 'ls' shows me what is in the room.
- 'cd' lets me walk to another room.

---

### Commands I learned

'''bash
pwd
ls
cd
'''

---

## VS Code Keyboard commands

⌘ + S          Save
⌃ + `          Open Terminal
⌘ + Shift + P  Find Anything
⌘ + P          Find a File
⌘ + /          Comment a Line

---

### Questions I have

- What is a bash command

---

### Notes

Today I started my AI Developer Bootcamp!

---

### Developer Vocabulary

| Word | My Explanation |
|------|----------------|
| Terminal | A place where I type commands to my computer. |
| Shell | The program that interprets my commands. |
| zsh | The shell my MAC uses by default. |
| Command | An Instruction given to the computer. |
| Argument | Extra information given to a command. - Example:  echo "Hello" echo = command; "Hello" = argument. |
| Bash | The language I use to tell my computer what to do. |
| pwd | Shows where I am. |
| ls | Shows what's in the current folder. |
| cd | Moves me to another folder. |
| Bug | Something unexpected that happens in my instructions or code. |
| Debug | Finding out why something happened and fixing it. |
| Literal | Computers do exactly what I tell them, not what I meant. |
| mv | A command that moves or renames files. |
| cat | show me what is inside this file. |
| touch | creates a file. |
| > | sends output to a file. |
| mv | renames/moves files. |

---

## Developer Tip

VS Code has its own built-in Terminal.
This means I can write code, keep notes, and run commands without switching between applications.  

One window = my complete development workspace.  

---

## My First Debugging Story

Problem:

I tried to write text into a file:

echo "Hello, Future AI Developer!" > hello-world.txt

The terminal showed:

dquote>

What I learned:

The terminal interprets special characters differently than humans do.

The exclamation point (!) had a special meaning in zsh.

Solution:

I used single quotes:

echo 'Hello, Future AI Developer!' > hello-world.txt

Debugging is about testing small pieces until I find the problem.

---

## Debugging Lesson: Commands vs Text

The terminal treats the first word I type as the command to run.

Example:

echo "Hello"

means:
- echo = the program/command
- "Hello" = the text I want it to display

Typing only:

"Hello"

makes the computer look for a program named Hello.

The computer follows instructions literally.