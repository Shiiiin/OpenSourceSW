# Advanced Programming in UNIX Environment

Note taking from class



** How to use Mark Down**



README.md
여러분들이 저장소에 리포지토리를 추가하면 아래와 같은 README.md 파일이 생성되는 것을 볼수 있습니다! 이 파일에는 프로그램에 대한 설명 및 개발과정 등을 작성해 어떤 프로젝트인지 한눈에 알수 있게 하는것이 좋습니다. 그렇다면 이 파일은 어떻게 작성해야 하는 걸까요?

마크다운 언어 문법
README.md파일의 확장자를 보면 md 즉 markdown으로 된 파일임을 알수 있습니다. 그렇다면 markdown 문서를 작성하려면 어떻게 해야할까요?

깃허브의 README.md는 markdown 및 HTML을 지원합니다!
작성할때 한글과 같이 아래 마크다운 문법을 지키면서 작성하시면 됩니다~

0.다음줄로 넘기기
마크다운은 다음줄로 넘기려면 문장의 끝에 스페이스바를 두번누르던지 엔터를 두번눌러야지 다음줄로 넘어갑니다.

1.글자 크기
글자크기는 # 을 이용하여 정

할수 있으며 아래와 같이 #의 개수에 따라 크기가 달라집니다.

글자크기는 # 을 이용하여 정할수 있으며 아래와 같이 #의 개수에 따라 크기가 달라집니다.



>\# 안녕하세요
# 안녕하세요

>\#\# 안녕하세요
## 안녕하세요

>\#\#\# 안녕하세요
### 안녕하세요

>\#\#\#\# 안녕하세요
#### 안녕하세요

>\#\#\#\#\# 안녕하세요
##### 안녕하세요

>\#\#\#\#\#\# 안녕하세요
###### 안녕하세요

2.강조하기
강조는 **을 강조하고 싶은 부분의 양쪽을 감싸주면 됩니다.

나는 배가고프다
나는 **배**가고프다

3.기울임체
기울임체는 ***을 기울이고 싶은 부분의 양쪽을 감싸주면 됩니다.

나는 배가고프다
나는 ***배가고프다***

4.취소선
취소선은 ~~을 취소선을 넣고싶은 부분의 양쪾을 감싸주면 됩니다.

으아아아ㅏ 과제 하기 귀찮다
으아아아ㅏ ~~과제~~ 하기 귀찮다

5.코드 넣기
코드 넣기 기능은 ```언어 ```로 감싸주면 되고 자동 하이라이트를 지원합니다.

#include<stdio.h>
int main(void)
{
    printf("Hello Interface!\n");
    return 0;
}
```c
#include<stdio.h>
int main(void)
{
printf("Hello Interface!\n");
return 0;
}
```

6.인용
인용을 하려면 문장 앞에 >를 붙이면 됩니다.

이것은 인용이다

>이것은 인용이다

7.URL 링크
url이 들어나는 링크 방법
https://help.github.com/categories/writing-on-github/

url이 들어나지 않게 링크 하는 방법
바로가기
[바로가기](https://help.github.com/categories/writing-on-github/)

기타 다른 기능
이모티콘을 출력하는 Emoji, URL링크, 이미지 등은 아래의 github 공식 사이트에서 확인할수 있습니다 https://help.github.com/categories/writing-on-github/
