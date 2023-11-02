# git_connect

# git 설치 기본값 그대로 설치
# 시작 버튼에서 git bash 실행

```
git config --global user.name "yj"
```

```
git config --global user.email "dnzidzid4477@gmail.com"
```

```
# 정보 확인하기
```

```
git config --list 엔터
```

![image](https://github.com/aeiouzz/git_connect/assets/145514483/cbb59cef-b9fe-4108-9762-b1d702160aaa)

⬆️ :p 컴퓨터에 한번만 설정하면 됨



# Github에 코드 업로드하기

1. 비주얼 스튜디오 코드 초기화하고 원하는 폴더만 다시 넣기!
2. 터미널 누르고 git init 입력 폴더 보기 숨긴 항목 보기 체크!
3. .git 폴더 생성됨
4. 파일 올리기
```
5. git add . 입력
```



# 히스토리 만들기
```
6. git commit -m "내가 적고 싶은 메세지" 입력 ( m 메세지, 메세지에는 한글이 반응함)
```

# 깃허브 폴더랑 내 로컬 폴더랑 연결(깃업에 프로젝트를 올릴 폴더를 먼저 만들어야 한다)
깃허브에 폴더 만들어서 리드미 파일 X 하고  주소 비주얼 스튜디오 코드에 입력
![image](https://github.com/aeiouzz/git_connect/assets/145514483/b3c83ac7-69af-4463-babc-abaab659d231)
```
7. git remote add origin https://github.com/aeiouzz/webstandard.git 입력
```

```
8. git remote -v 입력 (연결되었는지 확인하는 거)
```

```
9. git push origin master 입력
```
