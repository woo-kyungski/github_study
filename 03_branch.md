### branch

- 브랜치 생성

```bash
$ git branch 브랜치명
```

- 브랜치 목록

```bash
$ git branch
```

- 브랜치 이동

```bash
# git checkout 까지만 입력한 상태에서
# tab tab => checkout 가능한 브랜치명 확인 가능
$ git chechout 브랜치명
(브랜치명) $
```

```bash
$ git log --oneline
fd03945 (HEAD -> master) all date update
a523c3e (origin/master, origin/HEAD) Create README.md
```



- 브랜치 생성 + 이동

```bash
$ git checjout -b 브랜치명
```



- 브랜치 병합

```bash
(master) $ git merge 브랜치명	
# 커밋 페이지: i(insert) - 수정 - esc - : - wq
```

반드시 master 브랜치에 브랜피를 병합

- 브랜치 삭제

```bash
$ git branch -d 브랜치명
```

- 브랜치 강제 삭제

```bash
$ git branch -D 브랜치명
```

merge가 되지 않은 브랜치는 강제로 삭제해야 함









