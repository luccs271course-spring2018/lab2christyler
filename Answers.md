# What is the complexity of each of the four search methods in terms of array or list size n?
findTeamPosition - both are done linear so the tasks are always multiplied by n constantly.
findTeamMinFunding - same concept as findTeamPosition, but is comparing integers instead
findTeamMinFundingFast - binary search uses log, so with log base 2 of n, it runs through that until it finds a solution


# What happens in the case of binary search if the array is not sorted?
- The search would not work efficiently, because a binary search looks at specific values of a half and if the array is
unsorted, results will most likely be inaccurate.


# What is the purpose of constructor argument validity checking?
- To constantly be able to check that the program is working and to give us the opportunity to catch the errors early on,
instead of having a less chance of catching what may be wrong with the code.


# What is the purpose of using the keyword `final` with variables and arguments?
- It states the argument that the variable should not ever need to be changed or modified


# What are alternatives to using `Optional` and how do they compare?
- Optional is an alternative to the return value and concept. Optional can return a null (since in this case as well
answers can be null)
