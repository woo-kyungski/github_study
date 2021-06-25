## 원격 저장소(remote repository)

## 기본 설정

1. 로컬 git 저장소 준비
2. github repository 생성
3. Repository default branch 변경



## 명령어

### 원격 저장소 주소 추가

```bash
# git아, 원격 저장소 주소 origin이라는 이름으로 추가할 건데, 
# 주소는 이거야.
$ git remote add origin https://github.com/woo-kyungski/github_study.git
```



### 원격 저장소 목록 보기''

```bash
$ git remote -v
```



### 원격 저장소 삭제

```bash
$ git remote rm origin
```



### 원격 저장소에 업로드(push)

```bash
#git아 업로드 할 건데 origin이라는 이름으로 저장해 둔 원격 저장소에 master 브랜치의 commit 내역들을 업로드 할 거야.
$ git push -u origin master
```

