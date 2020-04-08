# Configuration
* Fix scrolling to active item in sidebar on load (#214)
* Style caption link for code and literal blocks
* Fix inconsistent font size and line height for autodoc "raises" and "returns" (#267)
* Fix last_updated notice appearing in same line as copyright notice (#704)

.. code-block:: python
   :emphasize-lines: 3,5

   def some_function():
       interesting = False
       print 'This line is highlighted.'
       print 'This one is not...'
       print '...but this one is.'
