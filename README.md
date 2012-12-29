ost_head2head
=============

For this assignment, we'll be creating a new command called head2head that can be used to compare objects one pair at a time until a ranking between all objects is obtained using the Condorcet method.  The idea is similar to what you might see on websites like http://www.greatmovieexperiment.com/.


1. Before executing the program "head2head", add the complete path of script
 directory to the PATH variable and export it to environment. For example,

	export PATH=$PATH:$PWD

If not, you could only execute the program using ./head2head instead of
head2head.

2. In the option name vote, the assignment requirement says "If 1 or 2 is
entered, the vote should be recorded appropriately. Otherwise, an error
should occur". I think it's not a good design decision. Therefore, when two
random items in the specific category are printed to stdout, there are three
choices: 1, 2 or q for quit. If 1 or 2 is entered, the vote should be
recorded appropriately. If q is entered, the program exit with success
status, in this case, 0. If other any character(s) is entered, the program
would give user a hint that only 1, 2, or q should be entered and display
the same two items to stdout that user would make choice again.
