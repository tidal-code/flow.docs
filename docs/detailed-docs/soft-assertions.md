---
layout: default
title: Soft Assertions
parent: Detailed Docs
nav_order: 10
---


# Soft Assertions

Suppose you have a group of data from a table and verify them one by one, using hard assertions
would not be a good idea. The test would fail immediately if you use hard assertions and you 
will never get to know what the rest of the values were. 


## Using Soft Assertions

To use soft assertions with Tidal flow library, you just need to prefix your verification
methods with ```Soft```. The assertion result will be kept in memory and will never be thrown immediately.

Examples:

```java
    Soft.verify("Description", "Test").contains("Te");
    Soft.verify("Description", result).isTrue();
```


## Throwing Soft Assertions

To throw soft assertions, you need to call the below method.

```java
new ErrorStack().execute();
```

Just make sure that you call it only at the end of the test execution. If you are using test hooks,
you can use it with the after hooks.



