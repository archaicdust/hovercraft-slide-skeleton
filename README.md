
### Generate your silde from reStructuredText

[hovercraft](https://github.com/regebro/hovercraft)

Example:
[example/index.html](http://htmlpreview.github.io/?https://github.com/archaicdust/hovercraft-slide-skeleton/blob/master/example/2015-06-01_ming.html#/step-1)

# ENV

    # Optional: pyvenv
    $ pyvenv hovercraft-env
    $ source hovercraft-env/bin/activate

    $ git clone https://github.com/archaicdust/hovercraft-slide-skeleton.git
    $ cd hovercraft-slide-skeleton

    $ pip3 install -r requirements.txt

# Usage

After edit slide.rst

   $ make html

## Tip - [LiveReload](https://github.com/livereload/LiveReload)

    $ bundle exec guard

### prerequisite

+ [Guard](https://github.com/guard/guard)
+ [guard-livereload](https://github.com/guard/guard-livereload)


Setting

    $ rvm use <ruby_version>
    $ rvm gemset create guard-livereload

    $ rvm gemset use guard-livereload
    OR
    $ rvm use <ruby_version>@guard-livereload

    $ gem install guard-livereload

    $ bundle exec guard

For example

    $ rvm use 2.2.1
    $ rvm gemset create guard-livereload
    $ rvm gemset use guard-livereload

    $ cd hovercraft-slide-skeleton
    $ bundle install
    $ bundle exec guard
