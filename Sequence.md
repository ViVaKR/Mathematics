# 수열

> 일정한 규칙으로 나열된 수의 열  
> 나열된 각 수를 그 수열의 항이라 함  
> $\left\{a_n\right\}  1, 3, 5, 7, \cdots, 2n-1$  
> $a_1, a_2, a_3, \cdots, a_n, \cdots$  
> 위와 같이 차례로  
> <b>첫째항(제1항), 둘째항(제2항), 셋째항(제3항), $\cdots$ , n째항(제n항)</b>
> 특히, n째항 $a_n$ 을 <b>일반항</b>이라하고, 
> 일반항인 $a_n$인 수열을 간단히 $\left\{a_n\right\}$으로 나타냄

## 일반항
> 수열의 규칙성을 나타내는 식으로 $a_n$ 표시함  
> 1 부터 차례로 2을 더하여 얻은 수를 나열한 1, 3, 5, 7, 9, $\cdots$ 은  
> $a_1=1, a_2=3, a_3=5, a_4=7, \cdots$ 인수열이다.  
> 이때 일반항은 $a_2 = 2n-1$ 이므로  
> $\left\{2n-1\right\}$으로 나타낼수 있다.  

## 등차수열

* 뺀것이 같은 수열 (`deference`)  
* 더하는 일정한 수를 <b>공차</b>라고 함  
* `첫째항, 공차` 만 알면됨  
* 즉, 첫째항이 `a` 이고 공차가 `d` 인 수열의  
* `일반항`(수열의 규칙성)
* $a_n = a + (n - 1)d$  
* e.g. 첫째항 -1, 공차 3일 등차수열  
  * $a_n = -1 + (n-1)3 = 3n$
* e.g. 4, 1, -2, - 5
  * $a_n = 4 + (n - 1)(-3) = -3n + 7$

## 등차중항

* 세 수 $a, b, c$ 가 이 순서로 등차수열을 이루면 
* $b-a = c-a \quad \therefore 2b = a + c, b = \frac{a + b}{b}$
* e.g. 세 수 2, x, 18 이 이 순서로 등차수열을 이룰 때, x 의 값을 구하시오
  * x 가 2와 18의 등차중항이므로 
  * $x=\frac{2 + 18}{2} = 10$
* $\cdots, b-d, b, b + d, \cdots$


## 등차수열의 합

* `n` 번째 항까지 등차수열의 합은 역순으로 한번 더 써준 후
* 동일한 열의 각 항을 더한 후 2로 나누어 줌
* e.g. 첫째항이 `a`, 공차가 `d`, 제n항이 `l`인 등차수열의 합
* $S_n = a + (a + d) + (a + 2d) + \cdots + (l - d) +  l$
* $+$
* $S_n = l + (l - d) + (l - 2d) + \cdots + (a + d) + a$
* $=$
* $2S_{n} = (a + l) + (a + l) + \cdots + (a + l) + (a + l)$
* $S = \frac{n(a + l)}{2}$
* $S = \frac{n(2a + (n-1)d)}{2}\quad$ $\because \quad l = a + (n - 1)d$

## 극한

> 수열 $\{a_n\}$ 에서 $n$ 이 한 없이 커질 때,  
> $a_n$의 값이 일정한 실수 $\alpha$에 한없이 가까워 지면  
> 수열 $\{ a_n \}$ 은 $\alpha$에 수렴한다고 한다.  
> 이때 수열 $\{ a_n \}$ 의 극한 또는 극한값이라 하고,  
> 다음 과 같이 나타 낸다.  

$$\displaystyle\lim_{n \to \infty} a_n = \alpha$$
$$또는$$
$$n \to \infty\quad 일때\quad a_n \to \alpha$$

---

$a_n = c$ 상수일때는 같아 질수 있음

---

* $lim$ 는 극한을 뜻하는 `limit` 의 약자로 리미트라고 읽음
* 기호 $n \to \infty$ 는 $n$이 한없이 커진다는 뜻
* $\frac{n}{n + 1} \cdots \to$ `1에 수렴` $\displaystyle\lim_{n \to \infty} a_n = 1$
* $\frac{1}{n}\cdots\to$ `0에 수렴` $\displaystyle\lim_{n \to \infty} b_n = 0$
* $\frac{(-1)^n}{n}\cdots\to$ `진동하면서 0에 수렴` $\displaystyle\lim_{n \to \infty} c_n = 0$
* $\displaystyle\lim_{n \to \infty} d_n = \alpha\to\cdots$ ($\alpha$ 는 상수) 인 경우에도 $\{ d_n \}$ 은 $\alpha$ 에 수렴한다고 함

## 발산

> 수렴하지 않으면 발산

1. 양의 무한대로 발산: $n$ 한없이 커질 때 $\{ a_n \}$ 이 한없이 커질 때, $\displaystyle\lim_{n \to \infty} a_n = \infty$
2. 음의 무한대로 발산 : $n$ 한없이 커질 때 $\{ a_n \}$ 의 값이 음수이면서 그 절대값이 한없이 커질 때, $\displaystyle\lim_{n \to \infty} a_n = -\infty$
3. 진동 : $n$ 한없이 커질 때 $\{ a_n \}$ 이 수렴하지 않으면서 양의 무한대나 음의 무한대로 발산하지 않을 때

---
