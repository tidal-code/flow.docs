---
layout: default
title: Detailed Docs
nav_order: 3
has_children: true
permalink: /docs/detailed-docs
---

# Detailed Documentation

Tidal Flow is built with ease of use and convenience in mind. 

The intention is to reduce the complexities you face while using other assertion libraries. 
You can basically do all assertion types with just one method. It will intuitively know the correct assertion type to use, 
whether it's a String, Number, Date, Map, Array, or any other assertion type.

The format is like below:

```java
    verify("Description", TYPE).assertionMethod(args);
```

This is all what you need to remember.

<br>
<p>
The 'TYPE' will determine what assertion method to be shown to you. If it is of String type, it will show the
relevant String type assertion methods. For Number assertion types it will show Number type assertion methods.
</p>

For example, if it is String type, it will show

```java
    verify("Description", "String").contains(String);
    verify("Description", "String").startsWith(String);
    verify("Description", "String").matchesPattern(String);
    ....
    
```

For Number type, it will show

```java
    verify("Description", NUMBER).isGreaterThan(Number);
    verify("Description", NUMBER).isPositive();
    verify("Description", NUMBER).isInRangeOf(Number1, Number2);
    ...
```


For Array types, it will show

```java
    verify("Description", ARRAY).hasSize(int);
    verify("Description", ARRAY).isTypeOf(Class);
    verify("Description", ARRAY).isEmpty();
    ....
```

This is quite intuitive and you don't have to remember different types of assertion methods for each types.


## Hard Assertions and Soft Assertions

Hard assertions would terminate the test execution when it fails. In many scenarios that would be the desired effect we needed.
In certain other situations, we might need to verify a list or group of results and need to know how many passed and how many failed.
Soft Assertions serve that purpose. 

<br>
How hard it is to use Soft Assertion with Tidal Flow library? 

Just add ```Soft``` before the verify method. Thats all you need. 


For example:

```java
    Soft.verify("Description", NUMBER).isGreaterThan(Number);
    Soft.verify("Description", NUMBER).isPositive();
    Soft.verify("Description", NUMBER).isInRangeOf(Number1, Number2);
```

<b>NOTE:</b> Soft Assertions need to be thrown later in the test hooks or when test is finished. 
That setting is entirely up to you to be completed. Soft assertions will not be thrown otherwise.
<br>
For more details visit the [Soft Assertions]({{ site.url }}/flow.docs/docs/soft-assertions) page.

We have covered the most important part of the documentation. The further pages show in detail the available methods.