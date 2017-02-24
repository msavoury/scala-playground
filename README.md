# scala-playground
##General Scala Knowledge
- Scala has no checked exceptions
- An ```if``` expression has a value
- The ```void``` type is ```Unit```
- Don't use ```return``` in a function/method

##Implementation
Types are inferred but can be specified
```
val myName = "Joe";
val container:String = null; //Specifying as a String explicitly since it can infer much from 'null'
```
There is no concept of a primitive type in Scala. All 'primitive' are objects and methods can be called on them
```
1.toString // "1"
```
