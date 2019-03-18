# Title

## Learning Goals

- Describe the functionality of arguments
- Define methods that accept arguments

## Introduction

In the real world, many interactions are customized or specific to our
day-to-day experiences. For example, if you go to a coffee shop, they may take
down your name to call up your order when it's ready. If visit a doctor's
office, they may call your name when it's your turn to be seen. Variables that
we experience in real life often need to be translated into to programs.

## Describe the functionality of arguments

When we log into email, social media, or any other user-based platform, what do
we normally see after logging in?

Our name somewhere on the account, right?

So far, we've only discussed how to create methods that return static
information. For example:

```ruby
def greeting
  puts "Hi, Ruby programmer!"
end

greeting
```

As amazing as this method is, it's still pretty static. It hard-codes, or
directly specifies, the name of the person we are greeting as `"Ruby
programmer"`. If we wanted to build a method that can greet *anyone*, we'd need
to be able to add input into the body of the method.

Just like with a greeting, we'd want our method to be more dynamic, more
abstract, and *more re-usable*. Remember our DRY (Don't Repeat Yourself)
principle? The method should maintain the elements that will always be the same,
no matter who we greet, but allow us to change, or swap out, the name of the
person we are greeting. This is dynamic, as opposed to "hard-coded".

## Define methods that accept arguments

< modify the original text to go here >

## Conclusion

In order to create dynamic functions in Ruby, pass in arguments, also known as
parameters, that can be referenced in the body of the method. This gives us a
lot more flexibility to maintain efficient code bases, as well as to apply
real-world concepts when building our programs. You'll learn more about
arguments in future lessons.

## Resources
