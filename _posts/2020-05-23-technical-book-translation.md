---
layout: post
title: 기술서적 번역 회고
categories: [노트, 회고]
tags: [회고, 번역]
author: hyunseo
img_path: /assets/img/posts/2020-05-23-technical-book-translation/
---

2019년 10월부터 올해 4월까지 기술서적 한 권을 번역했다. 상당히 오랜 시간을 들인 작업이었고 번역하는 동안 느낀 점이 많아 글로 남기려고 한다.

<br>

## 시작하기

### 적당량의 여유는 필요하다.

SW마에스트로 교육 과정이 끝나고 당시 휴학한 나로서는 이후 찾아올 공백기가 무서웠다. 아무것도 하지 않으면 아무 일도 일어나지 않는다. 가치 없는 시간을 만들지 않으려고 할 일을 꾸역꾸역 만들었다. 하지만 너무 과해 몇 번이나 약속했던 일을 포기했던 기억이 난다. 다음부터는 일과 삶의 균형을 맞추려 노력해야겠다.

![trip](trip.jpg){: .shadow width="1548" height="864" }
_가끔은 여행도 가자!_

<br>

### 왜 번역인가.

번역을 할 때 원문을 해석하며 영어를, 이해한 내용을 풀어쓰며 국어를, 풀어쓰는 과정에서 글과 예제 코드를 실행해보며 기술을 배울 수 있다고 생각한다. 2019년 당시 나이로는 고등학교 1학년이었던 나에게 번역은 그 어떤 일보다 효율이 좋은 일이라고 생각했다.

<br>

### 처음에는 기술서적이 아니었다.

처음에는 외국 블로그 글이나 기사에 대해 번역을 하려고 했다. "상업적"이나 "공식적"인 작업은 생각조차 하지 못했다. 나에겐 주의를 끌 만한 약력이 없었으며 경험도 부족했다. 물론 게임 매뉴얼이나 플러그인 한글 패치는 해본 적 있지만 이런 작업물이 주는 느낌은 공식적인 작업물이 주는 느낌과는 아주 달랐다.

그래서 깊게 고민하지 말고 단순하게 생각해 알만한 사람들에게 물어보기로 했다. 번역을 해봤던 지인부터 한빛미디어 같은 여러 출판사까지 번역을 시작하는 방법에 관한 이메일을 보냈다. 정말 많은 조언을 받았다.

오만하고 두려운 게 없었던 나에게 진심 어린 답변을 해준 출판사에 다시 한번 감사한다.

<br>

시간이 흘러갔고 SW마에스트로가 끝날 때쯤에는 번역이란 작업에 푹 빠져, 결론적으로는 책임을 지는 글을 써보기로 했다.

![thank-email](thank-email.png){: .shadow width="1548" height="864" }
_귀찮게 해서 죄송합니다_

<br>

### 컨택하기

마음을 정하니 컨택은 의외로 간단했다. 번역하고자 하는 책을 고르고, 읽어본다. 한국에 해당 책 출판을 담당하는 에이전시(출판사)가 있다면 그 에이전시에 이메일, 전화 또는 직접 방문하여 이 책을 번역하고 싶다는 의사를 밝히면 되었다. 보통 오라일리 미디어<small>O'Reilly Media</small> 책은 한빛미디어에서 번역&출간하고 팩트<small>Packt</small> 책은 에이콘에서 번역&출간한다.

나는 직접 방문을 택했고 편집자님과 대표님을 만났다. 편집자님께서 원래 번역하려고 생각했던 책은 다른 역자가 맡아 진행 중이고 챗봇 프로젝트를 하시던데 챗봇 책을 번역해보는 것은 어떻냐고 권유해주셨다. 기술서적이라 머뭇거렸지만 감사히 권유를 받아 11월부터 번역을 시작했다.

<br>

### 샘플 번역

출판사와 번역가가 처음 작업을 진행할 때는 샘플 번역을 한다. 이 샘플 번역은 일종의 리스크 관리로, 역자는 후에 번역 스타일에 불합리한 의견이 들어오는 것을 방지하며 출판사는 역자의 문체가 출판사가 원하는 문체인지 확인한다. 기판력이 작용하기 전에 변호사가 가져오는 양질의 판례와 비슷한 역할을 한다고 보면 된다. 그렇게 일주일간 샘플 번역을 했고 품질이 나쁘지 않아서인지 전체 번역을 진행하기로 했다.

![git-project](git-project.png){: .shadow width="1548" height="864" }

<br>

## 번역하고 느낀 점

### 원칙의 필요성

6개월간, 번역하는 동안 생각했던 것보다 계절은 빨리도 변해갔다. 3개월 차에 세운 나만의 두 가지 원칙이 아니었더라면 분명 난항을 겪었을 것이다.

간단하지만, 정말 커다란 원칙들이다.

> 원칙 1. 어색한 문장이 나오면, 문장을 하이라이트하고 넘어간다.<br>원칙 2. 한 장을 마치면 전 장에서 하이라이트한 문장을 수정한다.

<br>

막히는 것에 대한 두려움이 줄어들어 1차 번역을 빠르게 끝낼 수 있었다.

기술서적인 만큼 객관적이어야 한다. 하지만 역자도 자연어처리 능력을 갖춘 사람인지라 주관적 관점의 영향으로부터 완전히 자유로울 수 없다. 쉽게 말해 다른 사람도 내가 아는 것을 마땅히 안다고 생각하는 ‘지식의 저주’를 멀리해야 한다는 뜻이다.
나는 문장을 짧게는 10일, 길게는 15일 시간을 두고 수정함으로써 이 문제를 완화했다. 사랑하는 아부디의 피드백도 열심히 받았다.

<br>

### 용어 통일

번역한 내용을 검토하다 보면 가끔 잘못 쓰인 이상한 문장이나 용어가 보인다. 이 문장이 단 한 번만 쓰이는 문장이라면 수정하면 그만이다. 하지만 그럴 때마다 괜스레 겁이 났다.

**문장**이라면

_내가 전 장에서도 이런 비슷한 문장이 있었던 것 같은데 그 문장도 이상하게 쓴 게 아닐까?_

**용어**라면

_앞에서는 이렇게 안 쓴 것 같은데_  
_띄어쓰기를 했었나?_

하물며 자주 등장하는 단어에 오류가 있다고 생각해보자.

…… 아니다 생각하지 말자.

<br>

편집자님이 번역을 진행하면서 용어집이 있으면 무척 좋다고 얘기하셨는데 나는 엑셀을 잘 다루지 못해서 IT 용어사전 사이트를 만들었다. ~~사실은 손이 근질근질해서 토이프로젝트를 하고 싶었다!~~

번역이 끝난 지금은 누구나 기여가 가능하게끔 사이트를 열어두었지만, 지금까지 PR은 없었다.

![term-dictionary](term-dictionary.png){: .shadow width="1548" height="864" }
_[IT서적 번역용 온라인 용어집](https://hyunseochoi.github.io/translation-terminology/)_

<br>

또한 용어집과 함께 단어 번역 규칙도 정리했다. 'not를' ⇒ '낫을' 이라고 써야 할지 아니면 '"나트"를' 이라고 써야 할지 많이 고민했다. 불도그(불독) 같은 단어도 마찬가지다.

<br>

### 무엇이 중요한가요?

나는 이해와 경험이 무엇보다 중요하다고 생각한다. 인문학적 소양과 독서에서 오는 다학제적 관점도 필요하다.

물론 영어는 기본이다. 그러나 소위 말하는 공인인증 시험에서 고득점을 받거나 영어 원서를 쓱 보면 자연스레 이해하는 등의 거창한 영어 실력은 필요 없는 것 같다. 물론 도움은 되겠지만 역자는 결국 이해하는 쪽에 서는 사람이다. 뜻만 번역할 것이라면 번역기를 사용해도 된다.

컴퓨터 용어로 번역자를 설명하자면 인터프리터, 미들웨어 플랫폼쯤 되는 것 같다.

저자는 원서로 나에게 영어로 주제에 관해 열심히 설명한다. 번역자는 그 주제를 이해하고 이걸 다시 독자에게 설명해야 한다. 이해하는 것과 이해시키는 것은 차원이 다른 문제이며, 이 과정에서 설명에 필요한 지혜가 필요한 데 결국, 이 지혜는 이해와 경험에서 오는 것 같다.

<br>

### 문장은 신뢰다.

~~나는 맛춘뻡을 잘 지키는 편이다. 진시미다.~~

맞춤법. 그 세글자를 지키기 위해 나는 큰 노력을 기울였다. 평소 책을 읽으면서 철자 오류를 발견하면 눈살을 찌푸리는 편이라 더욱 엄격하게 검토했다. 하지만 이 맞춤법이라는 놈은 비 오는 날의 지렁이처럼 시도 때도 없이 고개를 치켜세우는 것이다.

다음은 내가 제일 두려워하는 두 마리의 지렁이를 소개한다.

- 괄호 지렁이: 괄호(묶음표라고도 부름)이 길어지다 보면 조사를 잘못 사용하기 십상이다. 이 문장처럼!
- 맞왜틀왜맞 지렁이: 이따가와 있다가처럼 철자 오류가 없지만, 뜻이 다른 단어가 있다. 주의하자!

<br>

+@ 맞춤법과는 관련이 없지만 문장을 다듬는 과정에서 도움을 준 책이 있다. 두껍지도 않고 에피소드 형식이라 재밌게 읽었던 책을 하나 추천하겠다. 피동을 남용하고 번역투에 익숙해진 우리의 문장을 꼬집어주는 좋은 책이다.

[내 문장이 그렇게 이상한가요?](https://www.notion.so/1759aedae5ab472fbd5d97be72178888)

<br>

이 글을 보는 모두가 '적의를 보이는 것들'을 멀리하는 사람이 되었으면 좋겠다.

<br>

### 저자와 연락

2020년 2월 초에 조금은 예상했던, 하지만 원하지 않았던 순간이 다가왔다. 검수하던 코드의 테스트 데이터셋이 누락되었다는 것이다.

무엇을 해야 할 지 몰라 편집자님 찬스를 쓰기로 했다.

내가 해야 하는 일은 연락할 수 있는 이메일, 영어 이름을 출판사에 보내는 것뿐이었다. 그러고 나서 며칠을 남은 챕터를 번역하며 기다렸다.

![reply](reply.png){: .shadow width="1548" height="864" }
_요약 ⇒ 역자가 저자에게 직접 메일을 보내도 괜찮습니다_

<br>

에이전시에서 해외 출판사에 이메일을 보낸 결과 내가 원저자와 연락하여 해결하기로 했다. 이렇게 나의 첫 비즈니스 메일은 바다를 건너는 영광을 누리게 되었다.

부끄럽지만 아래는 나의 첫 비즈니스 이메일이다.

```
Dear Shrey Shivam,

I am HyunSeoCHOI translating the book "Building an Enterprise chatbot (97814250334)".
Thank you for writing a good book.

I am writing to enquire about the resources you use in the book.
For example, (P.131)dataset/amzn_food_review_small.txt or something like (P.172)data/corn_review.txt and (P.180)1~10_neg/pos.txt.
If there is a separate storage space with the above data, I want you to let me know.
For now, I am referring to the next GitHub page. (refer: https://github.com/Apress/building-an-enterprise-chatbot)

I look forward to hearing from you.

Sincerely,
HyunSeo CHOI
```

<br>

이후로 다섯 건 정도 메일을 더 주고받았고 데이터셋도 깃 저장소에 올릴 수 있었다.

<br>

## 왜 출판이 되지 않았을까?

번역을 하고 계약에 따른 금액은 받았다. 하지만 작업을 마치고 몇 달이 지나도 도서 초안이 나오지 않아 나는 자연스레 출간할 수 없겠다고 짐작했다.

사실 번역을 하면서도 어느 정도는 짐작했던 부분이다.

크게 세 가지 이유가 있다. 2번과 3번은 원서에도 적용되는 부분이다.

1. 글로벌 챗봇에 관한 도서라 영문 자연어 처리를 다룬다. 영어 언어 체계와 한국어 언어 체계가 달라 하나의 모듈로 관리하기 쉽지 않다. ⇒ 독자층이 좁다.
2. 챗봇이 크게 대두되며 구축 방식에 변화가 생겼다. ⇒ 어제까지 사용하던 기술이 오늘에 이르러 구식이 되는 일은 IT 업계에서 흔한 일이다.
3. 포지션이 애매하다. 프로그래밍 능력이 없어도 만들 수 있도록, 또는 로우한 부분부터 개발하는 등의 컨셉이 확고하지 않았다. '프로그래밍 없이 -만들기'나 '밑바닥부터 시작하는 -' 시리즈가 많이 나오는 이유와 일맥상통한다. ⇒ 본 책의 구성은 얕고 넓어 흥미를 돋우기에는 충분하지만, 깊지 않아 배움의 갈증을 채우기에는 부족하다. ~~나에게는 장점이었다.~~

<br>

근 6개월을 공들인 작업이고 원문이 기술서적이다 보니, 돈보다는 커리어를 위해 번역을 하는 경우가 많다. 나 역시 커리어에 대한 욕심이 생겼다. 아쉽지 않다면 거짓말이다.

다시 출판 업계에 뛰어들 때는 복잡한 비즈니스는 잊고 흥망성쇠를 지켜볼 수 있는 나만의 책을 출간하고 싶다.

<br>

### 다음 계단

누구보다 빠른 행동력을 자랑하는 나는 번역이 끝난 후 다목적 출판사를 차렸다. 사업자 등록도 하고 세금에 관해 공부하며 회계 자격증도 취득했다. 이제 기회가 올 때까지 기다리면 될 일이다.

![fat](fat.png){: .shadow width="1548" height="864" }

<br>

번역을 하며 전달하는 개발자를 꿈꾸게 되었다. 과학적 분석력과 인문학적 감수성을 융합한 레이첼 카슨처럼.

<br>

## 감사한 분들

- 저자 → 양질의 콘텐츠를 써 주어 감사한다. 다루는 범위가 넓어 내 나름대로 챗봇의 개념을 정리할 수 있었다.
- 에이콘출판 → 내세울 게 아무것도 없던 고등학생에게 기회를 주어 감사한다.
- 편집자 → 번역 기간에 문제를 맞닥뜨렸을 때 가장 많이 의지했던 분이다.
- 아버지 → 우주 최강이신 아부디의 도움을 받지 못했다면 번역 작업이 배로 고되지 않았을까.
- 나 → 누가 뭐래도 나 자신이 제일 자랑스럽다.