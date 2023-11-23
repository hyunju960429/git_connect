# git_connect

# git 설치 --> 기본값으로 그대로 설치했음

# 시작버튼에서 Git Bash 열기(실행)

```
git config --global user.name "hyunju96"
```
#gitHib 가입시 입력한 이메일과 동일해야한다.
```
git config --global user.email "rnrdjcor12@naver.com"
```
#정보 확인하기
```
git config --list
```
![image](https://github.com/hyunju960429/git_connect/assets/145514544/b6154c6a-d932-40d6-9ccf-d37a556dda12)

⬆️위의 내용은 컴퓨터에 한번만 설정하면 된다.
-----------------
------------
# GitHub에 코드 업로드하기

1. 초기화

   ```
   git init
   ```
# .git이라는 폴더가 생성된다. (보기-숨김항목 체크)

2. 파일 올리기

   ```
   git add .
   ```

3. 히스토리 만들기

   ```
   git commit -m "내가 적고싶은 메세지"
   ```
# 메세지에는 한글이 가능함
# -m (메시지의 준말)

4. GitHub repository와 내 로컬 프로젝트랑 연결 (깃헙에 프로젝트를 올릴 repository를 먼저 만들어야한다)
# 아래 주소는 깃헙에서 만든 repository에서 복사해서 가져와야한다(repository 만들때 read me를 만들지 말아야란다)
   ```
   git remote add origin https://github.com/hyunju960429/webstandard.git
   ```

5. 잘 연결됐는지 확인(필수아님)
   ```
   git remote -v
   ```

6. GitHub에 자료 올리기
   ```
   git push origin master
   ```

# ⤴️여기까지 하면 GitHub의 repository에 자료가 올라간다.




   -----------------------------
   --------------------------------------------------------

![image](https://github.com/hyunju960429/git_connect/assets/145514544/ab00620c-364d-46a8-904d-11036054b9af)



   
