# How to contribute
In addition to writing code, joining in on discussions in the issues is a great way to get involved. Another great way to get started is to write additional testing and benchmarking scripts.

We are using Python and Keras because we believe they are beginner-friendly and easy to read. This is, to some extent, at the expense of speed. One of the biggest ways to help is to run some benchmarking scripts to see where the bottlenecks are and fix them!

## Git guide

1.keep upstream functional
2.write useful commit messages
commit --amend or rebase to avoid publishing a series of "oops" commits (better done on your own branch) (read this)
..but don't modify published history
3.prefer rebase master to merge master, again for the sake of keeping histories clean. Don't do this if you're not totally comfortable with how rebase works.
..but don't modify published history
4.keep pull requests at a manageable size

## Coding guide
We are using Python 2.7. It is recommended you use virtualenv to set up an environment. Once you've done so, you can install all necessary dependencies using

pip install -r requirements.txt
A good way to test if this worked is to run the tests

python -m unittest discover
Lastly, follow these guidelines:

remember that "code is read more often than it is written"
avoid premature optimization. instead, be pedantic and clear with code and we will make targeted optimizations later using a profiler
write tests in the tests/ directory. These are scripts that essentially try to break your own code and make sure your classes and functions can handle what is thrown at them
document and comment liberally
© 2020 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
