Python Syntax
=============


Identifiers
-----------

An identifier is a name used to identify a variable, function, class, module or other object.
Identifiers must start with a letter or underscore followed by zero or more letters, underscores
or decimal digits.

More precisely:

  identifier ::= (letter|"_") (letter | digit | "_")*

Remark
------

Python is a case-sensitive language and so 'Foo', 'foo' and 'FoO' are all different entities.

Reserved Words
--------------

Reserved words are inbuilt into Python and so may *not* be used as identifiers. All reserved
words are lowercase letters only.

  and
  or
  not
  exec
  assert
  finally
  break
  for
  pass
  class
  from
  print
  continue
  global
  raise
  def
  if
  return
  del
  import
  try
  elif
  in
  while
  else
  is
  with
  except
  lambda
  yield

Identation
----------

Python rigidly enforces line indentation as to denote blocks of code and hece the semantics
is scope with the ramification of code clarity. The number of spaces used to indent is arbitary
however the entire block must be consistently indented.

Multi-Line Statements
---------------------

Statements are terminated by a newline. However the 'line continuation character' (\) can be used
to denote escaping the newline to allow for multi-line statements. There is a context dependent
exception to the rule of newline statement termination, while statements are enclosed in [], {} or () there is no need for the line continuation character as there is no ambiguity in grammer.

Multiple line statements can be concatenated to a single line by seperating them with a semi-colon character (;). Multiple statements that consitute a single code block are said to be "suites" in Python terminology.

Quotations in Python
--------------------

String literals can be denoted by either single ('), double (") or triple (''' or """) quotes.
Where triple quotes are used for string literals that span multiple lines.

Comments in Python
------------------

Comments are denoted by preceeding them with the hash (#) character
