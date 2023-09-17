# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three bacticks(`)
- Not to be confused with quotation (')

```
#This code defines a factorial function that uses recursion to calculate the factorial of a given number.
#It then takes user input, calculates the factorial, and displays the result.

def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
num = gets.chomp.to_i

if num < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(num)
  puts "The factorial of #{num} is #{result}."
end

```

- When you can you should attempt to apply syntax highlighting to your Codeblocks

```ruby
#This code defines a factorial function that uses recursion to calculate the factorial of a given number.
#It then takes user input, calculates the factorial, and displays the result.

def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
num = gets.chomp.to_i

if num < 0
  puts "Factorial is not defined for negative numbers."
else
  result = factorial(num)
  puts "The factorial of #{num} is #{result}."
end

```
![Capture](https://github.com/AvatarFenix/github-docs-example/assets/145240919/0a9124be-4455-4324-85ef-355168bf09f5)

- Using HMTL to resize picture
- img width="150" src="https://github.com/AvatarFenix/github-docs-example/assets/145240919/0a9124be-4455-4324-85ef-355168bf09f5" 
<img width="150" src="https://github.com/AvatarFenix/github-docs-example/assets/145240919/0a9124be-4455-4324-85ef-355168bf09f5" />

- Good Cloud Engineers use Codeblocks for both Code and Erroes that appear inthe console.

```bash
Traceback (most recent call last):
example.rb:2:in `<main>': undefined local variable or method `undefined_variable' for main:Object (NameError)
```
> Here is an example of using Codeblock for an error that appears in bash.

## Step 3 - Use Github Flavored Markdown Task List

Github extends Markdown to have a list where you can check off items. [<sup>[1]</sup>](#external-references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

## Step 4 - Use Emojis (Optional)

Github Flavored Markdown (GFM) supports emoji shortcode.
Here are some examples.

| Name | Shortcode| Emoji |
| -----| -------- | ----- |
| Cloud | `:cloud:`| :cloud: |
| Smiley | `:smiley:`| :smiley: |
| Worried | `:worried:`| :worried: |
| Rage | `:rage:`| :rage: |

## Step 5 - How to create a table

You can use the following markdown format to create tables:

```markdown

| Name | Shortcode| Emoji |
| -----| -------- | ----- |
| Cloud | `:cloud:`| :cloud: |
| Smiley | `:smiley:`| :smiley: |
| Worried | `:worried:`| :worried: |
| Rage | `:rage:`| :rage: |

```

Github extends the functinality of Markdwon tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

## External References

- [GFM - Getting started with writing and formatting on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
- [GFM - Working with advanced formatting](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting)
- [Github Flavored Markdown Formatting Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Github Flavored Markdown Quoting Text](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables) <sup>[2]</sup>
