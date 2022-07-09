# Lint no list tutorial

A repo on which the [custom_lint] package has been setup:
  * The `lint_no_list` folder is where the lint must be implemented
  * The `app` folder is the folder where the lint is imported and can be tested

The goal is to implement a Flutter lint which warns the user not to use List and to prefer using IList instead. 

This lint should have an associated quick fix which allows the user to replace the List with an IList.
