Turning this program in a real program
--------------------------------------

 * Accept option to list all committed snippets
 * Accept to configure several snippets
 * Have helpful CLI documentation

Managing several computers
--------------------------

 * add _tag_ lists
 * remove order.run order.revert
 * automatic dependency on tag:basic and tag:common
 * reject removing tag:basic (can be done individually)
 * default action is to do tag:hostname

A _tag list_ is just a dependency beginning with tag:, maybe tag- or
tag/. All these dependencies are processed as another dependency file
(read lines one by one, run line).