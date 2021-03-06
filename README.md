# miniJava-Compiler 1.0
A miniJava compiler made using a subset of Java. This compiler was made in Java 1.8. For your convenience, I have spun up an AWS [instance](http://minijava-env.eba-vnw5cpj3.us-east-1.elasticbeanstalk.com/) that allows you to check your own miniJava code for Syntactic and Contextual Analysis.
EDIT: Disabled the AWS instance because bills.

### Syntactic Analysis
Checks the code to see if it follows the proper [grammar](https://github.com/Sunisc/miniJava-Compiler/blob/master/miniJavaGrammar.PNG).

### Contextual Analysis
Checks the code to see if Identification, references and types all match. The compiler will also generate an abstract syntax tree.

### Demo
Simply paste the following code into the textbox. If you were to paste the following code, the output will be the following.

*Code*

![Code][demo1]

```
class MainClass {
   public static void main (String [] args) {
      int tstvar = 1;
      System.out.println (tstvar);
   }
}
```

*Result*

![Result][demo2]

### Future updates

Feature | Completion Status (on local machine) | AWS Status
--- | --- | ---
Print line numbers of errors | DONE | IN DEVELOPMENT
Execute code | DONE | PLANNED
Release Source Code | MAYBE ;) | MAYBE ;)
___

### Version
1.0 miniJava Compiler by Surya - 5/11/2020

[demo1]: https://github.com/Sunisc/miniJava-Compiler/blob/master/demo1.PNG "Home Page"
[demo2]: https://github.com/Sunisc/miniJava-Compiler/blob/master/demo2.PNG "Results Page"
