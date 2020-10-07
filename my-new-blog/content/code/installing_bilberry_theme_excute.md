---
title: "Hugo 빌베리 테마 적용하기"
date: 2020-10-06T14:31:07+09:00
categories: ['Code']
tags: ['Hugo', 'Bilberry Theme', 'Blog', '고오오급 블로그']
author: "Dev_Marine"

---
Hugo를 이용한 빌베리 테마 설치 방법 입니다.

<!--more-->

__현재 적용된 테마를 적용하실려면 다음 내용을 그대로 따라 하시면 됩니다.__

- 일단 Hugo를 설치해줍니다.

```plaintext
hugo new site my-new-blog
```

- 휴고를 설치한 디렉토리로 이동한 다음 themes 안에 빌베리 테마를 깃헙으로 받아옵니다.<br>
그리고 다음 명령어를 그대로 복붙해줍시다.

```plaintext
cd my-new-blog/themes
git clone https://github.com/Lednerb/bilberry-hugo-theme.git
```

- 예제 사이트를 새 사이트에 복사를 시켜줍니다.
```plaintext
cp -r bilberry-hugo-theme/exampleSite/* ../
```

- 설치 테스트 적용
```plaintext
cd ../
hugo server -D
```
hugo server -D 를 하게되면 localhost:1313으로 로컬 환경에서 테스트 할 수 있습니다. <br>

현재 적용된 테마와 포스팅을 미리 확인하기 위해 로컬환경에 먼저 띄워서 테스트 해볼 수 있겠죠 ? 

- 필요에 따라 `config.toml` 파일을 수정하여 설정을 변경 할 수 있습니다.

PS: 사실 저도 기술 블로그가 처음이라 제대로 포스팅이 되는지 잘 모르겠네요 ㅎㅎ 앞으로 점차 나아지겠죠 ^^

