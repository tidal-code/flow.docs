---
layout: default
title: List Assertions
parent: Detailed Docs
nav_order: 7
---


# List Assertions



a) Method to check if the current list contains the specified elements.

```java
contains(T... values)
```

b) Method to check if the current list contains all the elements of the specified list.

```java
containsList(List<T> value)
```

c) Method to check if the current list does not contain the specified elements.

```java
notContains(T... values)
```

d) Method to check if the current list is empty.

```java
isEmpty()
```

e) Method to check if the current list is not empty.

```java
isNotEmpty()
```

f) Method to check if the current list contains elements of the specified class.

```java
ofType(Class<?> value)
```

g) Method to check if the size of the current list is equal to the specified value.

```java
hasSize(int value)
```

h) Method to check if the size of the current list is greater than the specified value.

```java
hasSizeGreaterThan(int value)
```


i) Method to check if the size of the current list is less than the specified value.

```java
hasSizeLessThan(int value)
```


j) Method to check if the current list is a sublist of the specified list.

```java
isSubListOf(List<T> value)
```


k) Method to check if the current list is a super list of the specified list.

```java
isSuperListOf(List<T> value)
```
