---
layout: default
title: String Assertions
parent: Detailed Docs
nav_order: 1.1
---


# String Assertions

The following methods are available for String Type Assertions.

a) Method to check if the given input string is not null or empty

```java
isNotNullOrEmpty();
```

b) Method to check if the given input string is null or empty

```java
isNullOrEmpty();
```


c) Method to check if the given string contains the value

```java
contains(String value);
```


d) Method to check if the actual value starts with the comparison value

```java
startsWith(String value);
```

e) Method to check if the actual value ends with the comparison value

```java
endsWith(String value);
```

f) Method to check if the actual value matches the given pattern

```java
matchesPattern(String charPattern);
```

g) Method to check if the 'actual' value contains the comparison values 'ignoring' case

```java
equalsIgnoringCase(String value);
```

h) Method to check the character count in the 'actual' value

```java
hasCharCount(int value);
```

i) Method to find the total count of alpha-numeric characters ignoring other characters

```java
hasAlphaNumericCharCount(int value);
```

j) Method to verify if the 'actual' value contains only letters

```java
containsOnlyLetters();
```
