# Simple Nesting Lab

## Objectives

- Access data from a nested `Hash`
- Add data to and change data within a nested `Hash`

## Introduction

Now that we've seen some examples of nested `Hash`es, the next step is to get
more comfortable with using them. In this lab, we're going to practice
accessing and updating data within a nested `Hash`.

## Instructions

You'll be filling out the content of a series of methods that we've defined for
you. All of the methods expect you to operate on the `programmer_hash` object,
which we've already defined and included in the body of each method. Use the
test suite to guide you. Each test is designed to tell you how to pass it.

Keep in mind that you are expected to get these tests to pass by adding or
changing information in the `Hash` *programmatically*. In other words, if you're
asked to, for example, change the value of a certain `Hash` key, *don't just
re-write the `Hash` with the new value!* Use the methods we've learned and
practiced in previous lessons.

To quickly review, here is an example of adding data to a `Hash`
programmatically:

```ruby
# good example

my_hash = {first: "i'm first!", second: "i'm second!"}
my_hash[:third] = "i'm third!"

puts my_hash
# > {first: "i'm first!", second: "i'm second!", third: "i'm third!"}
```

Changing a `Hash` by simply re-defining it is not the goal of this lab:

```ruby
# bad example

my_hash = {first: "i'm first!", second: "i'm second!"}
my_hash = {first: "i'm first!", second: "i'm second!", third: "i'm third!"}
```

**Hint:** In some of these methods, you will need to alter `programmer_hash`,
then make sure to _return_ the entire `Hash`, not just the altered value.

## Conclusion

Adding and updating data in a nested `Hash` is just like adding and updating a
normal `Hash`. If we know the structure, it is just a matter of using the right
combination of keys.

As we see examples of more complex data structures, we'll start to encounter
situations where we aren't 100% of the structure of a `Hash`. This is one reason
why getting familiar with programmatically changing `Hash` data is critical - we
won't always be able to _see_ the `Hash` we're changing. Instead, we'll have to
write logic that and correctly handles accessing and updating `Hash` data in a
more abstracted way.
