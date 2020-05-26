* README_EN.txt
* 2020.05.26
* tacklelib--3dparty--rapidxml

1. DESCRIPTION
2. LICENSE
3. REPOSITORIES
4. INSTALLATION
5. AUTHOR

-------------------------------------------------------------------------------
1. DESCRIPTION
-------------------------------------------------------------------------------
rapidxml patched sources fork from:
https://sourceforge.net/projects/rapidxml

From authors:

  RapidXml is an attempt to create the fastest XML parser possible, while
  retaining useability, portability and reasonable W3C compatibility. It is an
  in-situ parser written in modern C++, with parsing speed approaching that of
  strlen function executed on the same data.

  RapidXml has been around since 2006, and is being used by lots of people.
  HTC uses it in some of its mobile phones.

  If you are looking for a stable and fast parser, look no further.
  Integration with your project will be trivial, because entire library is
  contained in a single header file, and requires no building or configuration.

  Also available is its online Manual with a full and detailed reference.
  You may also like to check Boost.PropertyTree library, which presents a
  higher level interface, and uses RapidXml as its default XML parser.

  The author of RapidXml is Marcin Kalicinski.

The original library patched to fix these issues:

1. The `flags` function in the `xml_node` class to, for example, remember
   self-closed tags.

2. Use the same flag to enable print self closed tag by a user choice

3. The `print_node` function visibility fix.

-------------------------------------------------------------------------------
2. LICENSE
-------------------------------------------------------------------------------
Copyright © 2006, 2009 Marcin Kalicinski (kalita at poczta dot onet dot pl)
(see included text file "license.txt")

-------------------------------------------------------------------------------
3. REPOSITORIES
-------------------------------------------------------------------------------
Primary:
  * https://sf.net/p/tacklelib/3dparty--rapidxml/HEAD/tree/branches
    https://svn.code.sf.net/p/tacklelib/3dparty--rapidxml/branches
First mirror:
  * https://github.com/andry81/tacklelib--3dparty--rapidxml/tree/branches
    https://github.com/andry81/tacklelib--3dparty--rapidxml.git
Second mirror:
  * https://bitbucket.org/andry81/tacklelib-3dparty-rapidxml/src/branches
    https://bitbucket.org/andry81/tacklelib-3dparty-rapidxml.git

-------------------------------------------------------------------------------
4. INSTALLATION
-------------------------------------------------------------------------------
N/A

-------------------------------------------------------------------------------
5. AUTHOR
-------------------------------------------------------------------------------
Andrey Dibrov (andry at inbox dot ru)
