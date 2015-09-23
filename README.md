Learn To Program
================

#Ruby Week

Maker pre course Week two, working through [Chris Pine's Learn To Program book 2nd Edition](https://drive.google.com/file/d/0Bz17qR4zZedib0M5RnRwWFl3MUk/view).


Setup Instructions

 - Fork the repo to your own
 - Push to your own fork (check the upstream)
 - Open a pull request
 - Commit and push your code after *each* challenge so the CI server can check your work as you go along.


For submitting exercises from the Chris Pine Learn to Program Book

If you would like to run the tests associated with each chapter or even individual exercies you can do so as follows.  We use the RSpec library to test the code is working properly.  The RSpec library is available as a Ruby 'gem', which you can install in your computer by typing the following at the command line prompt:


$ gem install rspec


Once you have rspec installed as above, ensure that you have navigated to the root directory of this learn_to_program repo, e.g. 

cd /Users/JohnDoe/Projects/MakersAcademy/learn_to_program


Then if you'd like to check, say, your solution for the chapter 9 'ask' program you can run the following command for example:

$ rspec spec/ch09/

