# TIL (Today I Learned)

오늘 배운 것을 짧게 기록하는 저장소입니다.

## 목차

### Git
- [git](Git/git.md): Git 기본 명령어 정리
  - `init`, `status`: 저장소 만들기, 현재 상태 확인
  - `add`, `commit`, `log`: 변경 내용 저장하고 기록 보기
  - `remote add`, `push`: GitHub 같은 원격 저장소에 올리기
  - `restore`, `rm --cached`: 변경 되돌리기, 추적 해제
  - `mv`: 파일 옮기기·이름 바꾸기, LF/CRLF 경고 설명
  - `reset`, `stash`: 커밋 취소, 작업 잠시 치워두기

### Linux
- [linux](Linux/linux.md): 터미널 기본 사용법 정리
  - 명령어 구조(`명령어 옵션 대상`)와 경로(`~`, `.`, `..`, 절대/상대 경로)
  - `pwd`, `ls`, `cd`: 위치 확인하고 이동하기
  - `mkdir`, `touch`, `cp`, `mv`, `rm`: 폴더·파일 만들기, 복사, 이동, 삭제
  - `echo`, `>`, `>>`, `cat`, `head`, `tail`, `less`: 파일에 쓰고 내용 보기
  - `grep`, `|`, `which`, `--help`: 검색하고 도움말 보기

### Markdown
- [markdown](Markdown/markdown.md): 마크다운 문법 정리
  - 제목, 리스트(순서 있음/없음), 강조(굵게·기울임·취소선)
  - 코드(`` ` ``, 코드 블록), 링크, 이미지
  - 표, 인용문

### Etc
- [til](Etc/til.md): TIL 폴더 정리 방법
  - 다른 사람들의 TIL 정리 방식
  - 내가 정한 폴더 구조와 새 글 기록 순서

## 기록 방법

1. 주제 폴더 안에 `.md` 파일을 추가합니다. (새 주제면 폴더도 새로 만듭니다.)
2. 이 README의 목차에 링크를 추가합니다.
3. 커밋하고 push 합니다.
