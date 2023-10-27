# 수열

> 일정한 규칙으로 나열된 수들  
> 일반항

$n$ 이 한없이 커질때 일반항 $a_n$ 어떻게 변하는지 추측

정의역이 자연수인 함수


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
