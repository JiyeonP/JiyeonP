---
layout: post
title: Linear Algebra
subtitle: (3) Linear Algebra in Computer Science (작성전)
img: linear-algebra.png # Add image post (optional)
tags: [Mathematics, Linear Algebra, 선형대수학, 공학수학 1, 행렬, Matrix, Computer Science]
category: [Mathematics/LinearAlgebra]
---

## Computer Science 
**선형 방정식을 푸는 대표적인 알고리즘 중의 하나**

선형대수학은 이름 그대로 `선형적인 관계`를 이루는 변수들을 다루는 대수학의 한 분야이다.
많은 사람들이 선형대수학을 생각하면 행렬(Matrix)을 가장 먼저 떠올리곤 하는데,
이는 행렬이 선형적인 관계식을 표현할 수 있는 굉장히 용이한 구조를 가졌기 때문이다.   
선형대수학의 정의에 대해 조금 더 학문적으로 접근한다면,
`벡터 공간`과 `벡터`를 다루는 분야라고 말할 수 있다.
선형대수학은 비단 행렬뿐만 아니라 벡터, 선형 방정식 등 광범위한 개념을 포함하는데,
이들은 모두 `벡터 공간`과 `벡터`로서 정의될 수 있다.
그러니 먼저 벡터 공간과 벡터에 대해서 알아보자.

---
### 1. Gaussian Elimination
벡터 공간은 선형대수학에서 다루는 단위체의 `추상화(Abstraction)`이다.   
추상화란, 복잡한 개념에서 중요한 성질들만 꼽아 단순화하는 것이다.
우리는 추상화를 통해 복잡한 개념의 핵심을 쉽고 빠르게 파악할 수 있다.   
예를 들면 이렇다.
우리가 중학교 때 배웠던 인수분해 식을 생각해보자.

추상화를 적용하지 않았을 때:

<pre>

    (1+1)<sup>2</sup> = 1<sup>2</sup> + 2·1·1 + 1<sup>2</sup>
    (1+2)<sup>2</sup> = 1<sup>2</sup> + 2·1·2 + 2<sup>2</sup>
    (1+3)<sup>2</sup> = 1<sup>2</sup> + 2·1·3 + 3<sup>2</sup>
    ...

</pre>

추상화를 적용하였을 때:

<pre>

    (x+y)<sup>2</sup> = x<sup>2</sup> + 2xy + y<sup>2</sup>     (x, y 는 실수)

</pre>

우리는 <code>(1+1)<sup>2</sup></code>이 <code>1<sup>2</sup> + 2·1·1 + 1<sup>2</sup></code>로 인수분해됨을 발견했다.
<code>(1+2)<sup>2</sup></code>도, <code>(1+3)<sup>2</sup></code>도 동일한 형태로 인수분해 되었다.
왜 이런 형태의 등식을 만족할까?   
그것은 모두가 <code>(실수+실수)<sup>2</sup></code> 형태의 식이기 때문이다.   
따라서, 우리는 개별적인 인수분해 식들이라는 복잡한 정보의 총체로부터
<code>(x+y)<sup>2</sup> = x<sup>2</sup> + 2xy + y<sup>2</sup>     (x, y 는 실수)</code>
라는 추상화를 통해 핵심만을 얻어낼 수 있다.

### 2. 
선형대수학에서는 벡터 공간이라는 추상화를 도입하여,
아래의 5가지 특징들을 가지는 수학적 개념을 벡터 공간(***V***)이라 정의한다.

#### (1) 교환 법칙 Commutativity
***V*** 에 속하는 어떤 두 벡터 **a**, **b**에 대해서도

<pre>

    <b>a</b> + <b>b</b> = <b>b</b> + <b>a</b>

</pre>

가 성립한다.

#### 첨언
위의 벡터 공간 정의에서는 스칼라를 실수 범위에서 정의하였다.
이것이 일반적이나, 유리수 범위나 복소수 범위에서 스칼라를 정의하기도 한다.
따라서 우리가 정의한 벡터 공간은 엄밀히 말하자면,
<code>a vector space <b><i>V</i></b> over ℝ</code>이다.

    


---

### 3. Singular & Non-Singular 
지금까지 벡터 공간이 어떻게 정의되는지를 살펴보았다.
추상화로부터 유용한 성질을 끌어내어 사용하기 위해서는,
주어진 벡터 공간과 벡터의 성질을 표현할 수 있는 몇 가지 개념들이 필요하다.
가장 먼저 선형 독립에 대해서 알아보자.

#### (1) 선형 결합 Linear Combination
Vector space ***V*** 의 부분집합
***S*** = {**a<sub>1</sub>**, **a<sub>2</sub>**, ..., **a<sub>n</sub>**}에 대해





---

### 4. 

---

### 5. Crammer's Rule

---
### 출처
Advanced Engineering Mathematics, 10/e by Erwin Kreyszig

[](https://docs.aws.amazon.com)
