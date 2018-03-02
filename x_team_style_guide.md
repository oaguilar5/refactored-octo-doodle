# X-Team 51 Style Guide

<Commenting and good style is necessary for large teams of developers to efficiently collaborate on projects and understand each other's work.>

## Naming conventions

<Standard Java naming conventions, typical data structure identifiers.>

### Examples
* interfaces - (i.e. Decode)
* classes - (i.e. FishTank)
* exception types - (i.e. IllegalStateException)
* fields - (i.e. int numberOfFish)
* methods - (i.e. getID)
* parameters - (i.e. int x, int y)
* local variables - (i.e. boolean flag)
* instance constants - (i.e. final int ARRAY_SIZE)
* class constants - (i.e. final static int TREE_SIZE)

## Commenting style for public and private members of a class or interface:

<Private and public method headers for classes/interfaces are useful for identifying general purpose. Fields variables should be commented. Complicated algorithms should be presented with a high-level overview.>

### Examples

* classes:
/** Class Name (i.e. BalancedSearchTree)
*Description (i.e. implements a balanced search tree using an array data structure)
*/

* fields (i.e. //this field does nothing)

* constructors:
/** Constructor name (i.e. Public BalancedSearchTree)
*Description (i.e. Initializes the data fields required for the structure and instantiates objects)
*@param - (argument to pass to constructor for initialization)
*/

* methods:
/** Method name (i.e. lookupNode() )
*Description (i.e. Returns object if found)
*@param - (item to lookup)
*@return - (object if found)
*/

* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements (no brackets for single expression, one horizontal space for brackets, one vertical space for nested conditions)
  * switch statement (One horizontal space for brackets, one vertical space after each case)
  * while loops (no brackets for single expression, one horizontal space for brackets, one vertical space for nested conditions)
  * for loops - (no brackets for single expression, one horizontal space for brackets and characters in condition statement, one vertical space for nested conditions)
  * enhanced for loops - (no brackets for single expression, one horizontal space for brackets and characters in condition statement, one vertical space for nested conditions)
