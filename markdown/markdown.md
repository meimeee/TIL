# :book: markdown 작성법

![image-20210705142101753](markdown.assets/image-20210705142101753.png)

캡처 방법  : ctrl +  window + s



## 제목(heading)



제목은 문서의 구조와 관련이 있음.  h1~h6까지 존재하며, #을 붙여서 표현가능



### 목록(list)

#### 순서 있는 목록(Ordered List)

문장 맨 처음에 1. 하고 띄어쓰기 작성시  자동으로 목록

1. 수업을 한다.
   1. tab을 누르면 이렇게 들여쓰기 할 수 있음 
   2. shift tab을 누르면 앞쪽으로 옮길 수 있음 
2. 쉬는 시간을 갖는다.



#### 순서 없는 목록(Unordered List)

문장 맨 처음에 -를 쓰고 띄어쓰기 하면 자동으로 바뀜

- git
  - 리포 초기화 하기
  - 스테이징 하기
- CLI 명령어
- markdown 문법



## 본문 꾸미기 (Inline deco)

인용구 (있어 보이는 말) : > 이용

> 불행에 익숙해지지 말자. 



**Github** 특강을 듣는 월요일.   (별 두개로 감싸면 bold or contl B)

git은 *VCS*이다.  (별 한개로 감싸면 기울기)

폴더를 이동할 때는 `cd` 명령어를 사용한다. (backtic 으로 감싸면 하이라이트)

폴더를 생성할 때는 `mkdir` 명령어를 사용한다. 

code snippet



## 코드 블럭(cod block)

backquote(backtic) 3개 + enter 코드블럭 생성

```
a = 1
b = 2
c = a+b
print(c)

def my_func(n)
	return n

```



## 표 (table)

pipe()로 열을 구분하고 Enter로 표 생성. ctrl+enter로 행 추가

| 명령어 | 설명      | 사용 예시    |
| ------ | --------- | ------------ |
| mkdir  | 폴더 생성 | `mkdir aaa`  |
| cd     | 폴더 이동 | `cd aaa`     |
| touch  | 파일 생성 | `touch a.md` |



## 수식(Tex)

달러사인($) 두개로 블럭 생성, 내부 작성법은 따로 학습해야 함. 
$$
y=y(x,t)=Aeiθ
=A(cosθ+isinθ)
=A(cos(kx−ωt)+isin(kx−ωt))
=Acos(kx−ωt)+iAsin(kx−ωt)
=Acos(2πλx−2πvλt)+iAsin(2πλx−2πvλt)
=Acos2πλ(x−vt)+iAsin2πλ(x−vt)
$$

