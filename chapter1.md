---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

In this exercise, we will learn how to use the print function.

`@instructions`
Change the code so that it prints "hi there"

`@hint`
Did you change the words in the quotation marks?

`@pre_exercise_code`
```{python}
def repeat_print(content, iterations):
  for i in range(0, iterations):
    print(content)
```

`@sample_code`
```{python}
print("something")
```

`@solution`
```{python}
print("hi there")
```

`@sct`
```{python}
Ex().has_output("hi there", pattern = False).success_msg("Nice!").fail(msg="You need to change the words in the quotation marks in the print statement.")

```
