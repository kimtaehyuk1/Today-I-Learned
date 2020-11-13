# Today-I-Learned

레파지토리를 만들고 리드미 파일에 마크다운 언어 사용하기

💪마크다운 언어 사용법💪

1. 제목(헤더)
# This is a H1
## This is a H2
### This is a H3

2.
이메일에서 사용하는 > 블럭인용문자를 이용한다
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

3.
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑
    
    * 1단계
  - 2단계
    + 3단계
      + 4단계
      
4. 코드
4개의 공백 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작하여 들여쓰지 않은 행을 만날때까지 변환이 계속된다.

 들여쓰기
This is a normal paragraph:

    This is a code block.
    
end code block.

5.
코드블럭은 다음과 같이 2가지 방식을 사용할 수 있습니다:

1번째 방법
<pre><code>{code}</code></pre> 이용방식
<pre>
<code>
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }

}
</code>
</pre>

2번째 방법

```
public class BootSpringBootApplication {
  public static void main(String[] args) {
    System.out.println("Hello, Honeymon");
  }
}
```

6.
아래줄은 모두 수평선을 만듭니다.
* * *

***

*****

- - -

---------------------------------------

7.
기본적인건데요, 띄어쓰기(space)       여러 번은 한번과 같습니다. 
엔터를 한번 치면, 글이 붙어요.

엔터를 두번 치면 단락이 바뀌죠.


엔터 여러번 친다고 여러 줄이 띄어지는건 아니에요.


8.
😆
www.iemoji.com 
여기서 복붙하면 끝

9.
이텔릭체는 *별표(asterisks)* 혹은 _언더바(underscore)_를 사용하세요.
두껍게는 **별표(asterisks)** 혹은 __언더바(underscore)__를 사용하세요.
**_이텔릭체_와 두껍게**를 같이 사용할 수 있습니다.
취소선은 ~~물결표시(tilde)~~를 사용하세요.
<u>밑줄</u>은 `<u></u>`를 사용하세요.

10.
링크
[GOOGLE](https://google.com)

[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")

[상대적 참조](../users/login)

[Dribbble][Dribbble link]

[GitHub][1]

문서 안에서 [참조 링크]를 그대로 사용할 수도 있습니다.

다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.
구글 홈페이지: https://google.com
네이버 홈페이지: <https://naver.com>

[Dribbble link]: https://dribbble.com
[1]: https://github.com
[참조 링크]: https://naver.com "네이버로 이동합니다!"

11.
<img>로 변환됩니다.
링크과 비슷하지만 앞에 !가 붙습니다.

![대체 텍스트(alternative text)를 입력하세요!](http://www.gstatic.com/webp/gallery/5.jpg "링크 설명(title)을 작성하세요.")
