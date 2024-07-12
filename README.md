# sesac_study

금융데이터 분석과정 6기 스터디

🔥 내가 할일은 내가 아니면 할사람이 없다 🔥

### 목적

- 모두 수업의 내용을 이해할수 있도록 합니다.
- 편하게 질문하고 빠르게 수업 내용을 팔로우업합니다.

### **깃허브 브랜치 사용법!**

참고용 강의: https://www.youtube.com/watch?v=Z9dvM7qgN9s&t=309s

참고: https://eehoeskrap.tistory.com/666

1. Local 브랜치를 생성한다.(이름 자유)

```bash
git checkout -b dev_sdo
```

2. 개인 Remote 브랜치를 생성한다.(이름: dev\_초성 ex: dev_sdo)
3. 변경사항을 Local 브랜치에 commit 한다.

```bash
git add .
git commit -m "message"
```

4. 개인 Remote 브랜치로 commit한 Local 브랜치의 내용을 push한다.

```bash
git push origin dev_sdo
```

5. commit된 Remote 브랜치를 Remote 브랜치 중 dev에 Pull Request 한다.
6. 검수 후 merge 완료.

### 주의 사항

- ${\textsf{\color{red} 변경내용을 commit하기 전에 fetch를 통해서 최신변경 내용을 반영한다}}$
- Pull Request는 요청만 하고 건드리지 않는다. (merge를 누르면 안됨)
- 에러가 발생한 코드는 commit 하지 않는다.
- ${\textsf{\color{pink}GUI를 적극 사용한다.(ex: SourceTree, GitHub Desktop, Fork)}}$
