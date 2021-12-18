# I-am-a-developer

<p align="center">
  <img src="https://user-images.githubusercontent.com/66554164/140031991-a8cf74a9-d587-4d6d-b9b4-de5949b676ff.jpg" height="460px" width="580px">
</p>

## 개발자의 마음가짐, 힘이 되는 글/영상 모음 🚀

> 개발 공부 글이 아닌 개발 철학, 학습 방법, 마음가짐 등에 관한 내용의 글들입니다.

- 글 모음
  - [공개적으로 학습하라](https://han.gl/LT5BL)
  - [재능과 열정 없이도 프로그래밍을 하는 사람들](https://flearning-blog.tistory.com/237)
  - [웹 프론트엔드 개발자, 어떻게 준비해야 할까?](https://han.gl/0tuUJ)
  - [소프트웨어 학습법 & 협업 태도](https://han.gl/Pth0e)
  - [개발자용 운동팁 5가지](https://han.gl/msr8h)
- 영상 모음
  - [사랑받는 신입 개발자가 되는 법](https://www.youtube.com/watch?v=V60QQDA57SA)
  - [신입 개발자들이 제일 많이 하는 실수들](https://youtu.be/vtVpMBbRmlA)
  - [배달의민족 CEO에게 뽑고 싶은 개발자를 물어보았다](https://youtu.be/3H4umWD5bwI)
  - [주니어 개발자 ‘실제’ 이력서 첨삭해 보았습니다](https://youtu.be/1bcmmc2rTBE)

## 누구나 참여 할 수 있습니다!

두고두고 봐야하는 인상 깊었던 글, 영상을 공유 해주세요. 🤩

### PR(Pull Request) 하는 방법

#### 1. 저장소 fork 하기

<img width="872" alt="스크린샷 2021-11-03 오후 6 09 08" src="https://user-images.githubusercontent.com/66554164/140033985-bccb5939-0afc-410e-ac58-9148e0d3bd1b.png">

#### 2. 내 컴퓨터에 저장소 Clone 하기

```shell
  git clone https://github.com/본인계정/I-am-a-developer.git
```

#### 3. 원격 저장소에 Remote 설정하기

```shell
  git remote add 별명 https://github.com/원본계정/I-am-a-developer.git
```

- 원격 저장소 설정 현황 확인

```shell
  git remote -v
```

#### 4. PR용 branch 생성하기

```shell
  git checkout -b 브랜치명
```

- 브랜치 확인

```shell
  git branch
```

#### 5. README 파일에 글 또는 영상 넣기 😊

- 리드미 파일에 글 또는 영상을 넣어주신 후 모두 완료했다면, git add와 git commit을 진행 해주세요.

```shell
  git add .
  git commit -m "하실 말씀이 있으시면 자유롭게 적어주세요."
```

#### 6. PR용 branch에 push 하기

- ⚠️ push 진행 시 branch 이름을 명시 해주세요.

```shell
  git push origin 브랜치명
```

#### 7. fork한 저장소인 I-am-a-developer 저장소로 돌아오기

- 그럼 이제 Compare & pull request 버튼이 활성화가 됩니다.

  - 버튼을 눌러주세요!

- 글 또는 영상을 확인 후 Merge를 하겠습니다. 😀

#### 8. PR 승인 완료 후 branch 삭제하기

- 메인 저장소에 merge가 확인이 되면 작업이 끝났으니 삭제해도 됩니다.

- 다른 branch로 변경(checkout)한 후 아래 명령어를 실행해주세요.

```shell
  git branch -D 브랜치명
  git push origin :브랜치명 (혹은 git push origin --delete 브랜치명)
```

- 각각 local과 remote branch를 삭제해 주는 명령어 입니다.

- `git branch` 명령어는 local branch

- `git branch -r` 명령어, 깃허브 사이트에서 확인되는 branch는 remote branch입니다.

### Pull Request 참고 글!

[[GitHub] Pull Request(PR) 보내는 방법 : Contribution 하기](https://chanhuiseok.github.io/posts/git-3/)

[git 초보를 위한 풀리퀘스트(pull request) 방법](https://wayhome25.github.io/git/2017/07/08/git-first-pull-request-story/)
