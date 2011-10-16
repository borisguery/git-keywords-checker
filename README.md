Git Keywords Checker
====================

This hook let you check for common oversights like `var_dump()`, `die()` or `console.log()` and prevent you from commit them.

Installation
------------

To install hook, copy pre-commit file to your project .git/hooks/pre-commit:

    $ cp pre-commit .git/hooks/pre-commit;
    $ chmod +x .git/hooks/pre-commit;

Now, when you will make some modifications for code and will try to commit, GIT
will stop you and tells where problem exist.

About
-----

Such functions are likely to be never commited in a public repository or on live site, 
when you are on rush, you forget about them.

Contact
-------

*Boris Guéry*

Feel free to drop me a line at: guery.b@gmail.com

License
-------

See `COPYING`

