# miniJava-Compiler
A miniJava compiler made using a subset of Java. This compiler was made in Java 1.8. For your convenience, I have provided an AWS [instance] (http://minijava-env.eba-vnw5cpj3.us-east-1.elasticbeanstalk.com/) that allows you to check your own miniJava code for Syntactic and Contextual Analysis.

### Syntactic Analysis
Checks the code to see if it follows the proper grammar.

### Contextual Analysis
Checks the code to see if Identification, references and types all match.

### Demo
Simply paste the following code into the textbox. If you were to paste the following code, the output will be the following.

*Code*

```
class MainClass {
   public static void main (String [] args) {
      int tstvar = 1;
      System.out.println (tstvar);
   }
}
```

*Result*

```
Syntactic analysis ... 
Syntactic analysis complete: VALID miniJava expression


ContextualAnalysis ...
  IdentificationChecking ... 

  IdentificationChecking complete

  TypeChecking ...

  TypeChecking complete

Contextual analysis complete: VALID references and types
```

### Future updates
Print line numbers of errors - IN DEVELOPMENT
Execute code - PLANNED
Release Source Code - PLANNED
___

### Version
1.0 miniJava Compiler by Surya - 5/11/2020
