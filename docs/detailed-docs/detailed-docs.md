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
    contains(String);
    startsWith(String);
    matchesPattern(String);
    ....
    
```

For Number type, it will show

```java
    isGreaterThan(Number);
    isPositive();
    isInRangeOf(Number1, Number2);
```




