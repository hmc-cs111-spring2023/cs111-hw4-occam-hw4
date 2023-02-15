## Scala thoughts

#### Likes

Overall, my impression of Scala is that it is very intuitive.
To me, it seems most similar to Python, but with static typing.

I personally like the static typing because it can make the code a lot more
readable and make it easier to understand what the input and output of each
method is.

The code seems a lot more concise than a lot of other languages I've worked
with.
For example, the `if` `then` `else` syntax only has to have those keywords
without any braces, parentheses, or colons.
Another example is inserting values into strings just requires `s` before and
`$` in the string making it very readable.

A bit of a minor detail, but the I enjoy the syntax for `for` loops.
The arrow is a little strange, but just stating the iteration variable name and
then min `to` max seems so much more intuitive to me than using
`range(min, max)` or `i = min; i < max; i++`.

#### Dislikes

One thing I noticed was a bit difficult to do in Scala was creating blank lists.
I wanted to define a list with a specific type and size that I then update
values of in a loop, but I couldn't figure out how to initialize the list.

Another thing I found annoying was the lack of `break` statements.
I often find it useful to have sets of conditions in a loop that can cause it to
break out, but with this syntax, it seems like I would need to use a while loop
maybe with a bunch of cases which could make the code ugly.

Unrelated to the code itself, the documentation leaves a bit to be desired.
At least for the documentation we've been linked, it seems like the methods
provided are not a comprehensive list, and often don't have example code making
it difficult to learn for the first time. Maybe I just need to find a better
source of documentation though.

#### In between

In terms of return values, I haven't really decided whether I like Scala's
syntax or not.
On one hand, it is a lot cleaner to not have to write `return` in a bunch of
places, but on the other hand, it can make it more difficult to read code and
see all the places that it can exit the method and return the data.

---

After what I've learned so far, something I definitely want to learn more about
is the different types of data structures and what is easy to do with them.
Especially when working with more data, structures as simple as lists and
dictionaries can be extremely helpful, but I feel like I don't know how to use
even these structures to their full potential yet.