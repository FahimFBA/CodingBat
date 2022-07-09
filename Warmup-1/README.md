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


## [monkeyTrouble](https://codingbat.com/prob/p181646)

Question:

```
We have two monkeys, a and b, and the parameters aSmile and bSmile indicate if each is smiling. We are in trouble if they are both smiling or if neither of them is smiling. Return true if we are in trouble.


monkeyTrouble(true, true) → true
monkeyTrouble(false, false) → true
monkeyTrouble(true, false) → false
```

Codeblock:

```java
public boolean monkeyTrouble(boolean aSmile, boolean bSmile) {
  
}
```

Solution:

```java
public boolean monkeyTrouble(boolean aSmile, boolean bSmile) {
    return ((aSmile && bSmile) || (!aSmile && !bSmile));
}
```
