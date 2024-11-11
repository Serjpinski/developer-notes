# Dogmas

* Database triggers are evil. They hide business logic. Nobody checks triggers when analysing code. Only use them when needed (i.e. for atomicity).

* Names are important.
  * Names define what something is or what it does.
  * Names reflect your understanding of your own code.
  * Naming is both design and documentation.
  * Good naming is hard because design is hard.
  * Having trouble finding a good name is a code smell.
  * The points above apply to type and method names. For variable names:
    * The best name for a variable is the same name as its type.
      ```
      Human human;
      List<Child> children;
      ```
    * If you have two variables of the same type in the same context, then the best name is the key difference between the two.
      ```
      Human father;
      Human mother;
      ```
