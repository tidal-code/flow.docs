---
layout: default
title: Array Assertions
parent: Detailed Docs
nav_order: 4
---

# Array Assertions


a) Method to check whether the given map contains the specified keys

```java
containsKeys(T... keys);
```

b)Method to check whether the given map contains the specified values

```java
containsValues(V... values);
```

c) Method to check whether the given map contains the specified key-value pair

```java
containsKeyAndValue(T key, V value);
```

d) Method to check if the given map is empty

```java
isEmpty();
```

e) Method to check if the given map is not empty

```java
isNotEmpty();
```

f) Method to compare if the two maps are of the same type

```java
isSameTypeAs(Map<?, ?> value);
```