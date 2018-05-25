python-learn
============

Suggestions, tips, tricks, and a path to learn python more thoroughly

Path to python zen_
-------------------

.. _zen: https://www.python.org/dev/peps/pep-0020/

#. codecademy_ through section 8. Codecademy is great for beginners, and
   you can easily skip resources depending on experience or inclination. I
   recommend getting through at least section 8, and probably including
   section 11 (classes). This should cover most syntax and logical issues.

#. Start python interpreter locally by typing `python`. See you can create
   variables, print(...), and do all the same things as in a python file.
   Occasionally this may be useful for debugging :).

#. Final beginner recommendation: python docs are good, and include snippets
   that you may easily paste into a python file or run directly in the
   interpreter. Check docs for other material, and bounce between projects
   and referring to documentation_.

#. Create a hello world flask_ app, and be sure to eventually render at
   least one templated html file. Look into how requests are routed -
   registering flask '/' for example. This begins some design/architecture
   sense.

#. PDB tutorial_. Python is interpreted, and we can do a lot of fanciness
   based on that. Try the tutorial out, then optionally, play with things like:

   * make a method, then assign that method to a new varaible. invoke from pdb
   * print current values of variables to inspect/debug
   * define a new method/class only in pdb, make an instance

#. Create a web scraper_. Beautifulsoup_ can parse xml for you, and you can
   inspect values using pdb. Start with static xml, but you might consider
   using the requests_ library in the future. You could now make a flask app
   serving a REST endpoint.

.. _codecademy: https://www.codecademy.com/learn/learn-python
.. _documentation: https://docs.python.org/3/tutorial/index.html
.. _flask: http://flask.pocoo.org/
.. _scraper: https://medium.freecodecamp.org/how-to-scrape-websites-with-python-and-beautifulsoup-5946935d93fe
.. _tutorial: https://github.com/spiside/pdb-tutorial#pdb-101-intro-to-pdb
.. _BeautifulSoup: https://www.crummy.com/software/BeautifulSoup/bs4/doc/#quick-start
.. _requests: http://docs.python-requests.org/en/master/
