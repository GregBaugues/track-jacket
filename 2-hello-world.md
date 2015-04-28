# Ruby Basics

Ruby is a beautiful programming language. It was designed to be easy to read and a joy to write. It's based on C, but much, much simpler. 

Before we get into the Twilio stuff, let's talk about some programming basics. 

## 

Open iTerm2. You'll be dropped into your Home directory. 

Create a directory for your code: 
```
mdkir code
```

Now change into your code directory: 
```
cd code
```

List all the files in the directory: 
```
ls
```
Not much here. Just the ```.``` and ```..``` which is shorthand for "This directory" and "The directory before this one". 

Instead of putting all of our code into a single directory, we'll create a separate directoy for each project we're working on. When programming we typically use either dashses or underscores (_) in naming things. We also tend to not use caps (but as you'll see, there are exceptions for almost everything). 

Let's create one for our first, "Hello World," then change into that directory. 

```
mkdir hello_world
cd hello_world
```

Now let's create a file for our first ruby program. Ruby files have the extension ```.rb```. 

```
touch hello_world.rb
```

Now if we list the files again: 

```
ls
```

Alight, now let's open our file: 

```
subl hello_world.rb
```

And: 

```
puts "Hello World!"
```

Save. Then run it from iTerm: 

```
ruby hello_world.rb
```

Next, we'll talk about variables. Back to sublime: 

```
name = "Greg"
puts "Hello world. My name is: " + name
```

Run it again. 

We can also do: 

``` 
puts "Hello world, my name is: #{name}"
```

Variables can be a bunch of different things. For now we'll talk about: 

* strings
* numbers
* arrays





