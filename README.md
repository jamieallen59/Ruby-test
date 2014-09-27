Ruby Challenge
==============

![](images/try-ruby.png)

This was a challenge set to us on week 8 of Makers Academy to brush up our Ruby skills. Here's what we received:

## Friday test!

Here we're going to revisit the basics of Ruby. There are 41 questions - you don't have to do every single one (although if you can, that's great). You should be able to do at least 50% of them. They vary in level from quite easy to fairly hard. Work through them and check if they're correct by running the specs.

You should be able to answer most questions with a couple of lines of code, and just a few methods. If you're writing a long, complex solution, there's probably a better way.

To run the specs, just run

~~~
$ rspec questions_spec.rb
~~~

**Quick tip**: to run a single example, change `it` to `fit` on that example, then run

~~~
$ rspec questions_spec.rb --tag focus
~~~

:smile:

Good luck

### Rules

* Try and get the RSpec tests to pass (obviously without hardcoding the expected value)
* You shouldn't need any extra libraries or gems
* The cleaner your code the better!
* Googling is fine as usual

### Tips

* Use the ruby docs http://www.ruby-doc.org/core-2.0.0/String.html
* Try and break down the problems into smaller chunks. For e.g. if you google "How to select elements in an array that start with a", you won't have much luck. Try and find out a) how to select certain elements in an array, b) how to test if a string starts with an 'a'
* Don't forget Enumerable (advanced array methods)
* Read the specs and the comments - if you're still confused, just ask.
* Don't panic :wink:

-------------------------------

If you'd like to have a go, open the command line and check that it is all working:

### Run the tests
```sh
git clone git@github.com:jamieallen59/Ruby-test.git
cd Ruby-test
rspec
```

To have a go yourself, open 'questions_spec.rb' in your text editor. At the top, change "require 'answers'", to "require 'questions'"

```sh
rspec
```
You should see 39 test failures. Now, open 'questions.rb' and try to solve them.

Good luck!

