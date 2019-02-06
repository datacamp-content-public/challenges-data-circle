---
title: 'Week 1_Review Test'
output: html_document
description: ""
---

## True basics

```yaml
type: MultipleChoiceChallenge
key: 167A4VcDii9Ku
```

`@assignment1`
다음 중 변수(variable)에 값(value)을 지정해주기 위한 적절한 방법은?

`@assignment2`
다음 중 라이브러리 설치와 불러오기 코드가 제대로 된 것은?

`@options1`
- [`z = 3`]
- `z is 3`
- `z gets 3`
- `z -> 3`
- `z == 3`

`@options2`
- install.packages(dplyr)  /  library(dplyr)
- [install.packages('dplyr')  /  library(dplyr)]
- install.packages('dplyr')  /  library('dplyr')
- install.packages(dplyr)  /  library('dplyr')
- installpackages(dplyr)  /  library('dplyr')

---

## Blanks

```yaml
type: BlanksChallenge
key: 45ff8d1dee
```

`@context`


`@pre_challenge_code`
```{r}

```

`@variables`
```yaml

```

`@distractors`
```yaml

```

---

## Output_

```yaml
type: OutputChallenge
key: f19935c6ab
```

`@context`


`@code1`
```{r}
data(mtcars)

mtcars$new_variable = mtcars$mpg {{_fun1}} mtcars$cyl
```

`@pre_challenge_code`
```{r}

```

`@variables`
```yaml
fun1 :
	- '+'
    - '-'
    - 'x'
```
