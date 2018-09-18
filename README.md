Hello World

- What is it?

Strings are means of working with text in a programming language


- What does it do?

Provide a means of working with text, instead of having to work solely with numbers


- How do you use it?

Strings can be used in much the same way as numbers. We can store them, read them either in their entirety, or in part, and manipulate these to derive new strings.

LESSON:

Hello World
Fortunately, there’s much more to computer programming than working with numbers. Otherwise writing programs would be very difficult indeed! Strings enable us to work with words and text. In the tradition of almost every programming lesson ever, we’re going to print a string that says Hello World! It has long been a tradition in the world of programming languages to print out the statement that says “Hello World”, announcing yourself to the world as a developer, as well as testing the waters with a new language or concept (https://en.wikipedia.org/wiki/%22Hello,_World!%22_program).

 Runnable Example
 
 print("Hello World")
 
 ANSWER: Hello World
 
 print ('Hello World')
 
 ANSWER: Hello World
 
 

print('Then Mike said "what is that?"')

In Python, anything contained inside quotation marks is treated as a string. We can use double quotes (“”) or single quotes (‘’).

 Runnable Example

# Types Of Quotation
 
- What is it?

Defines the scope of a string

- What does it do?

Allows us to use different ways of creating and working with strings

- How do you use it?

We use the “”, or ” to define the scope of a string.

Types Of Quotation
We have different uses for each type of quotation. The reason for this is because the written language also has grammatical uses for quotations.

Runnable Example

print("Then Mike said "What is that?"")

ANSWER: What is that?

In the example above we get an error when we try to run it. The reason that we get this error is that when we try to open some double quotes to indicate that someone is saying something, Python thinks that that’s the end of the string. Python doesn’t know what the words that come after the closing quotation are. We can get around this by using single quotes.

 Runnable Example

print('Then Mike said "what is that?"')

ANSWER: Then Mike said "what is that?

Expand

Now we get this sentence printed out – Then Mike said: “what is that?” That’s all well and good, but what about apostrophes? What if we wanted to collapse what is into what’s? Well, we’re going to run into the same issue here because Python thinks that the apostrophe is the end of the string.

 Runnable Example

print('Then Mike said "what's that?"')

In order to get around this we’ll need to use an escape character, which we’ll take a look at next.

## Escape Characters

# Escape Character - Part One

- What is it?

A special character that allows us to format text inside of a string

- What does it do?

Allows us to create escape quotations, newlines, tabs, etc. inside of our string

- How do you use it?

The escape character is merely a backslash (\)

LESSON:
To use the apostrophe inside our string, we’re going to need to tell Python that the apostrophe is part of the string and not the end of the string. We can do this with the backslash (\).

Runnable Example

print('Then Mike said "what\'s that?"')

ANSWER: Mike said what's that?

The backslash is called an escape character. In some instances, we need to use the escape character to tell Python that we wish to do some formatting in our string. In this case, we wish to use an apostrophe within our string. We can also use the escape character for double quotes.

Runnable Example
 
print("Then Mike said \"what's that?\"")

ANSWER: What's that?

# Escape Character - Part Two
 
- What is it?

A special character that allows us to format text inside of a string

- What does it do?

Allows us to create escape quotations, newlines, tabs, etc. inside of our string

- How do you use it?

The escape character is simply a backslash (\)

 Challenge
 
Your challenge is to fix the string so that it will print out a sentence that says - “Apples and oranges,” remarked John. “Nope. I’d be inclined to disagree” replied Mike

The live code editor will do its best to point out any typos that you might make. So get stuck in and enjoy!

 Runnable Example
 
print('"Apples and oranges," remarked John."Nope. I’d be inclined to disagree," replied Mike')

ANSWER: Apples and oranges," remarked John."Nope. I’d be inclined to disagree," replied Mike

## Escape Character - Part Three

- What is it?

A special character that allows us to format text inside of a string


- What does it do?

Allows us to create escape quotations, newlines, tabs, etc. inside of our string

- How do you use it?

The escape character is merely a backslash (\)

Using the escape character followed by the letter n will create a new line.

Runnable Example

print("Hello\nThere")

ANSWER: Hello
There

After the word Hello, we use \n to create a new line. After that, we just have the word There. Once this code is run, Hello and There will be printed on two separate lines. Carriage return \r works in the same way.

Runnable Example
 
print("Hello\rThere")

ANSWER: Hello
There

## Escape Character - Part Four
 
- What is it?

A special character that allows us to format text inside of a string

- What does it do?

Allows us to create escape quotations, newlines, tabs, etc. inside of our string

- How do you use it?

The escape character is merely a backslash (\)

\t will indent a piece of text, much in the same way as the Tab key.

 Runnable Example

print("Hello\n\tThere")

ANSWER: Hello 
           There

In this example, we’ve combined the new line with the tab to better illustrate the tab. As we can see, the word Hello is at the furthermost left, but the word There is indented due to the use of the \t.

## Escape Character - Part Five

- What is it?

A special character that allows us to format text inside of a string

- What does it do?

Allows us to create escape quotations, newlines, tabs, etc. inside of our string

- How do you use it?

The escape character is simply a backslash (\)

 Runnable Example

print ("/|\\")
print ("/|\\")
print (" | ")

ANSWER: Arrow

## String Variables & Methods


# String Variables

- What is it?

A way of storing strings in memory


- What does it do?

Allows us to persist strings in memory, much like numerical values


- How do you use it?

We just assign a variable a value of a string, in much the same way as we declare numeric variables!

LESSON:
We now know how to create different types of variables using numbers, but we can store string variables too. We do this in the same way that we create a variable with a number. So without further ado:

 Runnable Example
 
my_string = "Hello World"

print(my_string)

ANSWER: Hello World

my_string = 'Hello World'

print (my_string)

ANSWER: Hello World

Here we’re just creating a variable called my_string with a value of Hello World and then printing out the value contained within that variable. Python will figure out what type this variable is, and therefore, we don’t have to worry about telling it that we wish to store a string.


# Concatenation
 
What is it?

A way of storing strings in memory


What does it do?

Allows us to persist strings in memory, much like numerical values


How do you use it?

We just assign a variable a value of a string, in much the same way as we declare numeric variables!

 String Variables - Part Two
Not only can we store strings in variables, but we can also use the addition and multiplication operators in Python. Adding strings is called concatenation.

 Runnable Example


Expand

Here we’ve constructed the string “Hello World!” by concatenating three strings together. Next, we’ll check out the multiplication operator.

 Runnable Example


Expand

If we have a string of boo and multiply it by 2, then we’ll end up with booboo. Python takes the string and will append the same string to the end of the first variable as many times as we multiply it by, which in this case is 2.  

# String Methods
 
What is it?

Will give us the ability to access specific pieces of a string, or the string in its entirety


What does it do?

Allow us to modify and manipulate string values


How do you use it?

We use string methods by using a dot (.) after the string, followed by the method name and a pair of brackets.

 String Methods
We can use methods on certain types of data. These methods will usually return some piece of information about the string in question or will return a modified version of the string. Let’s take a look at how some of these can work.

 Runnable Example

my_string = "HELLO WORLD"
my_string_lower_case = my_string.lower()

print(my_string_lower_case)

Here we declare a new variable called my_string and assign it the value of HELLO WORLD. On the next line, we declare a new variable called my_string_lower_case. We then use the string method called lower. To use this method, we use the dot notation (.) to access the lower method from my_string. Then we just use the empty parentheses to invoke the method. The .lower() method will give us the same string, but with all of the characters switched to lowercase. The result of this action is then assigned to the my_string_lower_case variable that we declared. In the Repl.it session above, try using the .upper(), .capitalize() and .title() methods and see what results they return.