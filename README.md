# Writting Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code. 
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.


- In order to create code blocks in markdown you need to use three backticks (`).
- Not to be confused with quotation mark (').

```
# Python program to print "Hello, CodeBlocks!"
print("Hello, CodeBlocks!")
```

- Highlighting code

```Python
# Python program to print "Hello, CodeBlocks!"
print("Hello, CodeBlocks!")
```
- Make a note of where the backtick button is located.
- but it may vary on your keyboard.
<img width="200px" src="https://github.com/zubi95/github-docs-example/assets/90310539/6fbee428-e7b4-4b07-852f-21a58d496373" />

- Good cloud engineers use codeblock for both Code and Errors that appear in the console.

```bash
  File "your_file.py", line 2
    print("Hello, World"
                        ^
SyntaxError: unexpected EOF while parsing
```
> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Task Lists

Github extends Markdown to have a list where you can check off items. <sup>[1]</sup>

- [x] Finish Step 1
- [] Finish Step 2
- [x] Finish Step 3
- [x] Finish Step 4

## Step 4 - use Emojis (Optional)

GitHub Flavored Markdown (GFM) Supports emoji shortcodes.
Here are some examples of emoji.

:cloud: 

## Step 5 - How to Create a Table

```md
| name| Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
```

## References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Basic writing and formatting syntax. (Github Flavoured Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text) 
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Table](https://github.github.com/gfm/#tables-extension-)
