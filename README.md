# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Enginner__ uses Codeblocks whenever possible

Because it allows others to copy and paste their code to replicate or research issues
- In order to create codeblocks in markdown you need to use three blackticks (```)
- Not to be confused with quotation (''')
  
```
#!/bin/bash
read -p "Enter a number and hit \"Enter\" " user_number
if [ $user_number -gt 10 ]
then
    echo "The number you entered is greater than 10."
else
    echo "The number you entered is less than or equal to 10."
fi
```

- When you can you should attempt to apply syntax highlighting to your codeblocks
```bash
#!/bin/bash
read -p "Enter a number and hit \"Enter\" " user_number
if [ $user_number -gt 10 ]
then
    echo "The number you entered is greater than 10."
else
    echo "The number you entered is less than or equal to 10."
fi
```
![20210209-ITQ_background-03B](https://github.com/Fsohmoek/github-docs-examples/assets/122841575/46497fa3-f25d-489c-a546-112a888767e9)
<img width="500px" src="https://github.com/Fsohmoek/github-docs-examples/assets/122841575/46497fa3-f25d-489c-a546-112a888767e9" />

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.
```bash
Traceback (most recent call last):
        2: from /usr/bin/irb:23:in `<main>'
        1: from (irb):1
RuntimeError: This is a custom error message
```
> Here is an example of using a codeblocks for an error thaht appears in bash.

When you can always provide a codeblock instead of a screnshot.
If you need to take a screenshot make sure it is not a photo from your phone.

> There are certain cases where its okay to take photos with your phone. This is when you are showing something like a keyboard, which does not appear on a computer screen.
If it render on your computer screen it should be a screenshot 

## Step 3 - Use GiHub Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish step 1
- [ ] Finish step 2
- [x] Finish Step 3

# Step 4 - Use Emojis (Optional)
 GitHub Flavored Markdown (GFM) supports emoji shortcodes

 Here are some examples:
 | Name | Shortcode | emoji|
 | --- | --- | ---|
 | Cloud | `:cloud:' | :cloud: |

## Step 5 - How to create a table

You can use the following markdown format to create tables.

```md
| Name | Shortcode | emoji|
| --- | --- | ---|
| Cloud | `:cloud:' | ☁️ |
| Cloud with lighting | ':Cloud_with_lighting:` | 🌩️ |
```
GitHub extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

![Secret Window Hidden Garden](secret-window/hidden-garden.md)
![Photo](assets/20210209-ITQ_background-02B.jpg)
##  External References

- ![GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- ![Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) 
- ![GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- ![GFM - Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet)
- ![GFM - Tables( with extensions](https://github.github.com/gfm/#tables-extensions-) <sup>[2]</sup>
