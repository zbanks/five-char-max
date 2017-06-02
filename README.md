
# Take a stance against long lines.

Clearly, no program should ever use more than 80 characters per line, for a whole host of reasons.
First and foremost, for readability and maintainability, it is important to have a solid standard, so we can adjust the width of our text editors appropriately.
As a secondary benefit, code can easily be transferred onto media that may have restrictions, and where adding line-breaks can be distracting, like print pages for review in a meeting, or punch cards.

But is 80 characters too high?
Some suggest 79, or even as low as 75, to allow for an 80 character wide terminal to fit the code with a few columns devoted to line numbers.
Clearly, ultimately, lower is better, as lower limits allow for the code to be used in more situations without reformatting.

## Introducing the `max4` standard.

In Python there is no excuse to ever use more than ~six~ ~five~ four characters per line.
This is plenty of width to code *any* conceivable program, and, in practice, is not overly restrictive.

Provided is a linter, `max4`, which will clean up your Python codebase to comply with the `max4` recommendation.
Using `max4` is incredibly easy:

    $ python max4 input.py compliant_output.py

`max4` is compatible with *both* Python 2 and Python 3, because 2 + 3 = ~5~ 4?

## We eat our own dogfood.

To show just how easy and freeing it is to code in `max4` Python style, the entire `max4` codebase is written in `max4` style.
Take a look at the `max4` source, and I'm sure you'll be compelled that this formatting style is more freeing than it is restricting.



