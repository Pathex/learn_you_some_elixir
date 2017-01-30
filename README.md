# Learn you some Elixir for great good

Welcome to this little tutorial for developer beginners. Here is what you are going to find out within the next steps:

 - What is github?
 - What is git and some basics
 - Soma basic paradigms and concepts about programming
 - We will dive into the Elixir programming language
 - ...and the Phoenix framework

Ready? Then let's start

## Git and github

Your first task is to create an account at guthub.com. Choose your nickname wise -> you shouldn't change it any more

Done? Great! Then please find out how to fork a repository and try it out... with this one. Continue this tutorial by opening this webside again... but on your fork!

### Welcome to your fork

From now on you should edit this document and add an answer by replacing the placeholders. But how do you actually do this?The first question will lead you to the answer:

#### What is git? How do you use it? WHat do the following commands do?

 - git clone
 - git add .
 - git commit
 - git push
 - git pull

Commit your answer ;-) (which you should do for every new answer you write.)

-git add put something in the index.
-git push upload your fille to github
-git clone download documents from github. You can then edit it after that.
-git commit confirm your changes
-git pull update your filles

#### You are currently on a fork. But what are forks used for?

Forking means to make copys from the original to edit it.

#### On github you can find the source code of many open source projects. Can you find the following code repositories? Please add the links in your answer:

 - The linux kernel source code
 - The boost graph library
 - The atom editor
 - The Elixir programming language
 - The Elixir poenix framework

 - https://github.com/torvalds/linux = linux
 - https://github.com/boostorg/graph = boost graph library
 - https://github.com/atom/atom/tree/master/src^= atom editor
 - https://github.com/elixir-lang/elixir = Elixir programming languages
 - https://github.com/phoenixframework/phoenix = phoenix framework

### Introoduction to programming

There are thousands of programming languages out there. Different programming languages follow different programming concepts called "paradigms". Now your first task:

#### Can you summarize the following paradigms:
 - Procedual programming
 - Object oriented programming
 - Functional programming

> write your answer here

#### Find two examples for each of the above paradigms

> write your answer here

### Elixir programming

We now want to dive into the Elixir programming language. Elixir is a very young and very modern programming language. It was created by Jose Valim who initially was a Ruby developer. But since Ruby has some disadvantages amd missing features he took the advantages of the two languages Ruby and Erlang and created a new language uniting the advantages of both languages into one: The nice syntax and ability of so called meta-programming from Ruby and the scalability and fault tolerance of Erlang. So let's get started wit some basics:

#### What is an actor?

> write your answer here

#### What is pattern matching?

> write your answer here

#### Some practise: Create your first actor in the Elixir interactive shell:

 - open a terminal and type `iex` which will open the "interactive elixir shell"
 - Type: `spawn fn -> IO.puts "Hello world!" end`

Congratulation! You just created our first actor! What had happen? `spawn` creates a new actor which gets some function as input which is then executed. In this case `fn -> IO.puts "Hello world" end`. The syntax `fn (args)-> body end` is one was to create a so called anonymous function in Elixir. In your case `args` was empty. So the function didn't get any input. Inside the body you found `IO.puts "Hello world!"` which translates to "write into the terminal the string `Hello world!`"

#### Time to get a bit more familar with the interactive Elixir shell and the language itself. Take a look into the Elixir's getting started guide: `http://elixir-lang.org/getting-started/introduction.html` and work through it (maybe until chapter 15).
