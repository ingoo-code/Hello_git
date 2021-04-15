# Hello_git
git 사용예제 저장소


## 1. git 설치하기

> https://git-scm.com/download/win
window 버전 설치하시면 됩니다.

git설치가 완료되었다면.

윈도우키를 눌러서 "Git  CMD" 파일을 실행해주세요.

이후 터미널 창이 나타나면

<pre><code>
git config --global user.name "name"
git config --global user.email "email@email.com"
</code></pre>

실행한뒤

<pre><code>
git config --list 
</code></pre>

실행시켜 결과물을 확인해주세요.   

## 2. Visual Studio Code 에서 Git 사용하기.

그다음 "Visual Studio Code" 이하 vscode를 실행시킵니다.   
앞으로 작업할 workspace[임의파일] 폴더 안에.   

```
git init 을 실행 시켜야합니다.
```

***
하지만 터미널을 처음 사용하시기떄문에. 간단한 터미널    명령어를 알려드릴게요.   

1. **ls** : 현 디렉토리 파일목록 보기
2. **cd** : 디렉토리 이동 명령어 
    ex ) cd .. 폴더뒤로가기 
         cd ./images  현폴더에서 images 폴더로 이동하기
3. **pwd**: 현 위치 
     ex ) 윈도우 환경이라면 
          C:\Users\PC-01\Documents\vscode\workspace\Hello_git2 이런식

***


간단한 터미널 명령어를 설명만 해드렸고.   
이번엔 vscode에서 터미널창을 여는방법을 알려드릴게요.   

vscode 활성화 상태에서. Ctrl + Shift + \` ` (Javascipt에서 배웠던 템플릿 이터널에 사용했던 )`
***

이후 터미널 창이 열렸다면. 
```
git init
git remote add origin [URL]
```

하시면   

<img src="https://github.com/ingoo-code/Hello_git/blob/master/images/git_login.png">   

창이 뜨게되고 

> [Sign in with your browser]   
 버튼클릭 하시면   

<img src="https://github.com/ingoo-code/Hello_git/blob/master/images/Sign_in_with_your_browser.png">

에서 초록색 버튼 클릭하시면 연결이 완료됩니다.  

이후 **vscode**에서 **index.html** 파일을 생성한뒤.  

**Body**영역에서 **Hello World** 를 작성한다음에.   


터미널 창에서 

```
git add .
git commit -m "커밋할 내용설명 영역"
git push origin master
```

하시고 나의 저장소에서. **index.html** 파일이 생성되었는지.   
확인해보세요.






