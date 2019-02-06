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
R에서 '주석'(comment)을 달기 위한 command는??

`@assignment2`
다음 중 변수(variable)에 값(value)을 지정해주기 위한 적절한 방법은?

`@assignment3`
다음 중 라이브러리 설치와 불러오기 코드가 제대로 된 것은?

`@options1`
- `%`
- `%*`
- [`#`]
- `@`
- `$`
- `*`
- `/*`

`@options2`
- [`z = 3`]
- `z is 3`
- `z gets 3`
- `z -> 3`
- `z == 3`

`@options3`
- 'install.packages(dplyr) / library(dplyr)'
- ['install.packages('dplyr') / library(dplyr)']
- 'install.packages('dplyr') / library('dplyr')'
- 'install.packages(dplyr) / library('dplyr')'
-'installpackages(dplyr) / library('dplyr')'

---

## Identify the class of an object

```yaml
type: OutputChallenge
key: 167oSz8A19yBt
```

`@context`


`@code1`
```{r}
x <- {{var1}}
class(x)
```

`@pre_challenge_code`
```{r}

```

`@variables`
```yaml
var1:
  - '-1.3'
  - 'c(5, 1)'
  - '"FALSE"'
  - '"TRUE"'
  - 'c(TRUE, FALSE)'
  - 'c("b", "a")'
  - 'c(FALSE, TRUE)'
  - 'TRUE'
  - 'FALSE'
  - 'c("-2", "3")'
  - 'c(12, -10)'
```

---

## Create a vector

```yaml
type: BlanksChallenge
key: 167y3A7MS2X70
```

`@context`


`@code1`
```{r}
{{var1}} <- {{_fun1}}({{var2}})
{{var1}}
```

`@pre_challenge_code`
```{r}

```

`@variables`
```yaml
var1:
  - 'x'
  - 'y'
  - 'z'
var2:
  - '11, 8, 10, 15'
  - '12, 17, 5, 19'
  - '-8, -4, 2'
  - '-9, -10, -2'
  - 'FALSE, TRUE, TRUE'
  - 'TRUE, FALSE, TRUE'
  - '"January", "June", "December"'
  - '"May", "June", "March"'
  - '"December", "September", "February"'
fun1:
  - 'c'
```

`@distractors`
```yaml
fun1:
  - 'x'
  - 'y'
  - 'z'
```

---

## Insert challenge title here

```yaml
type: BlanksChallenge
key: 8df54648f7
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
