---
title: Chapter 1
description: Basic operations.
---

## Ex 1.1

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: 2a2109b11f
```

Do some basic calculations using R

`@instructions`

Assign the result of 2 and 2 to an object called `x`.

`@hint`

User `<-` for assignment.

`@pre_exercise_code`

```{r}

```

`@sample_code`

```{r}

```

`@solution`

```{r}
# Calculate the sum of 2 and 2
x <- 2 + 2
```

`@sct`

```{r}
test_error()
test_object("x",
  undefined_msg = "Make sure you have defined `x`.",
  incorrect_msg = "Have you correctly assigned 2 + 2 to `x`?"
)
```
