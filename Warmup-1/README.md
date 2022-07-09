# Warmup-1

## [sleepIn](https://codingbat.com/prob/p187868)

Question:

```

The parameter weekday is true if it is a weekday, and the parameter vacation is true if we are on vacation. We sleep in if it is not a weekday or we're on vacation. Return true if we sleep in.


sleepIn(false, false) → true
sleepIn(true, false) → false
sleepIn(false, true) → true

```
Codeblock:

```java
public boolean sleepIn(boolean weekday, boolean vacation) {
  
}
```

Soltuion 01:

```java
public boolean sleepIn(boolean weekday, boolean vacation) {
  if (!weekday || vacation)
        return true;
    else
        return false;
}
```

Solution 02:

```java
public boolean sleepIn(boolean weekday, boolean vacation) {
    return (!weekday || vacation);
}
```