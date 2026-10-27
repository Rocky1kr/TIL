# TIL 정리 방법

## TIL이란
- Today I Learned, 오늘 배운 것을 짧게 기록하는 방식
- 블로그 글처럼 길게 쓰지 않고 짧은 메모를 쌓는다

## 다른 사람들의 방식
- 주제별 폴더 + 파일 하나에 글 하나 (가장 흔함)
- README에 전체 목차 만들기 (글이 많아지면 GitHub Actions로 자동 생성하기도 함)
    - GitHub Actions : 저장소에 push할 때 자동으로 작업을 실행해주는 기능
- 주제별 폴더에 주간 요약 추가하기

## 내가 정한 방식
```
TIL/
├── README.md        # 전체 목차 + 파일별 설명
├── Git/git.md
├── Linux/linux.md
└── Markdown/markdown.md
```

## 새로 기록하는 순서
1. 주제 폴더 안에 `.md` 파일을 추가한다 (새 주제면 폴더도 새로 만든다)
2. README 목차에 링크와 설명을 추가한다
3. 커밋하고 push 한다

```
git add .
git commit -m "message"
git push
```

## 정리할 때 쓴 명령어
- `git mv` : 파일을 옮기면서 git에도 알려주기 (자세한 내용은 [git.md](../Git/git.md))
