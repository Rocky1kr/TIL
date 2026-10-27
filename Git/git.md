# Git

## init
- `.git` 폴더 생성 (사진첩 생성)

```
git init
```
## status
- 현재 폴더의 git 작업상태

```
git status
```
## add
- staging area에 올리기 (무대에 올리기)
```
git add <filename>
```

## commit
- `.git` repository에 저장 (사진찍기)
```
git commit -m "message"
git commit --amend -m "fix message" # 마지막 커밋 메시지 수정
```

## log
- git 히스토리 출력
```
git log
git log --oneline #핵심만 출력

```
## remote add
- 원격 저장소 주소를 별명(origin) 으로 추가
```
git remote add origin https://github.com/Rocky1kr/TIL.git
```

## push
- 원격 저장소에 업로드
```
git push origin main
```

## add, commit, push (한 사이클)
```
git add .
git commit -m "update"
git push origin main
```

## restore
- 원복하기
```
git restore <filename>
git restore .
git restore --staged <filename> # 무대위에서 내린다
```

## git rm
- 추적중인 파일 추적에서 제거하기
```
git rm --cached <filename>
```

## git reset
- 브랜치를 앞 커밋으로 되돌려 커밋을 취소합니다.

```
git reset --soft head~1
git reset --mixed
git reset --hard

```
## git stash
- 작업중에 갑작스럽게 다른 장업을 진행해야 할 때, 작업중인 사항을 잠시 치워두는 방법.
stash를 사용해서 잠시 코드를 다른곳에 보관한 후에, 내가 원하는 branch에 적용할 수 있다.

```
git stash	
git stash apply	
git stash drop	
git stash pop
```








