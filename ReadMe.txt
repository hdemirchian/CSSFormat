This plug-in was generated for Lamps Plus Web development team for helping them with formatting their CSS files according to their own set of standards.  When installed, it will create a menu item called “LP CSS Formatter <version#>” under Edit menu.
Here is the list of standards it follows:
•	All curly braces should have a leading and trailing space
•	All colons should have a leading trailing space
•	Last parameter inside curly braces (even there is only one parameter) should have a trailing semicolon
•	All parameters inside curly braces should be sorted alphabetically
•	After sorting the parameters, all high priority parameters (parameters starting with ‘-’) should be moved to the top of the list and all low priority parameters (commented lines and parameters starting with ‘*’ and ‘_’) should be moved to the bottom of the list
•	Statements containing less than 4 parameters should be displayed on one line
•	Statements containing 4 or more parameters should be displayed in multiple lines.

Updates:
•	Fixed the bug of removing the last line if the selicolon was missing - sorry for taking so long to fix this.