# Installing Jekyll
ref.: https://cloudcannon.com/community/learn/jekyll-tutorial/

Install Jekyll - a simple, blog aware static site generator Ruby Gem.

Jekyll is a Ruby Gem that can be installed on most systems. It’s a straightforward process on both Mac and Linux, and only slightly more involved on Windows. Either way, it won’t take you long to get set up with Jekyll!
## How to install Jekyll

Jekyll is a Ruby Gem, which means you will need to install a couple of dependencies to allow the Gem to run on your system.

### You will need:

1.  [Ruby](https://www.ruby-lang.org/en/downloads/) version 2.4.0 or higher, including all development headers (check by running the command `ruby -v`)
2.  [RubyGems](https://rubygems.org/pages/download) (check by running the command `gem -v`)
3.  [GCC](https://gcc.gnu.org/install/) (check by running the command `gcc -v`, `g++ -v`)
4.  [Make](https://www.gnu.org/software/make/) (check by running the command `make -v`)

````ad-note
For a step-by-step walkthrough to help you install these, head to the [Jekyll installation guides](https://jekyllrb.com/docs/installation/) and follow the instructions for your system.
````
##Install Jekyll

Once you have done that you are ready to install the Jekyll gem. Go to your command line interface and run:
```shell
gem install jekyll bundler
```
## Final installation check

To check that the Jekyll installation has worked properly, run the following command:

```shell
jekyll -v
```