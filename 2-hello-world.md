# Hello World

Ruby is a beautiful programming language. It was designed to be easy to read and a joy to write. It's based on C, but much, much simpler. 

Before we get into the Twilio stuff, let's talk about some Ruby basics. 

Open iTerm2. You'll be dropped into your Home directory. 

Create a directory for your code: 
```shell
mdkir code
```

Now change into your code directory: 
```shell
cd code
```

List all the files in the directory: 
```shell
ls
```
Not much here. Just the ```.``` and ```..``` which is shorthand for "This directory" and "The directory before this one". 

Instead of putting all of our code into a single directory, we'll create a separate directoy for each project we're working on. When programming we typically use either dashses or underscores (_) in naming things. We also tend to not use caps (but as you'll see, there are exceptions for almost everything). 

Let's create one for our first, "Hello World," then change into that directory. 

```shell
mkdir hello_world
cd hello_world
```

Now let's create a file for our first ruby program. Ruby files have the extension ```.rb```. 

```shell
touch hello_world.rb
```

Now if we list the files again: 

```shell
ls
```

Now open Sublime, then go to file->open. Navigate to your home directory, click into your code folder, the open ```hello_world.rb```. 

Type this: 

```ruby
puts "Hello World!"
```

Hit cmd-s to save. Then run it from iTerm: 

```shell
ruby hello_world.rb
```

Congrats! You are officially a programmer! 

Next, we'll talk about variables. Think of a variable like a piece of Tupperwear with a label that says "fruit." We can put a banana in there. We can take the banana out and put in an apple. We might take out the apple and leave it empty. But regardless of what's in there, we'll just refer to container as 'the fruit container.'

A variable is a container for data.

Go back to sublime and add this to the end of your file: 

```ruby
name = "Your Name"
puts "Hello world. My name is: " + name
```

Go back to iTerm and run it again. As a shortcut, you can hit the up arrow to cycle through previous commands. 

```shell
ruby hello_world.rb
```

As the name implies, the contents of a variable can change (unlike a constant which we'll talk about later.) 

```ruby
name = "Greg"
puts name
name = "Karyn"
puts name
name = "Roy"
puts name
```

Notice there that we didn't use quote marks when doing the puts-ing. Look at the difference between these two: 

```ruby
name = "Greg"
puts name
puts "name"
```

Also, sometimes the plus signs get a little annoying to type out, especially if we're using a lot of different variables. Ruby gives us a syntax to drop a variable directly into a string. 

Try this: 

```ruby
first_name = "Greg"
last_name = "Baugues"
puts "Hello world, my name is: #{first_name} #{last_name}"
```

All the variables we've looked at so far are called Strings (short for "string of characters"). Variables can also be numbers: 

Try this: 

```ruby
num = 1
puts num
num = 10
puts num
num = num * 10
puts num
num = num - 10
puts num
```

That's it for now! 