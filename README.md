### CLI, Command Line Interface




# Command

command line interface 명령어를 정리합니다.



#### pwd

print working directory

현재 위치한 폴더를 출력하는 명령어



#### ls

list의 약자로 현재 폴더에 있는 모든 파일과 폴더를 출력하는 명령

``` shell
ls # 숨김 폴더는 출력 안함
ls -a # 숨김 폴더, 파일까지 모두 출력함
```



#### cd

change directory의 약자로 작업하는 폴더를 이동하는 명령어입니다.

```shell
cd <PATH> # 이동하고 싶은 폴더를 PATH에 입력, tab을 이용해 자동완성 기능 사용가능
```



#### 생성

- `touch`: 파일을 생성하는 명령어
- `mkdir`: 폴더를 생성하는 명령어





# Github로 협업하기

#### Git

- `git init`: 깃저장소를 생성한다.
- `git status`: 깃의 상태를 보여준다.
- `git add <Filename>`: working directory에서 staging area로 올린다.
- `git remote add origin <URL>`:
- `git remote remove origin`:  
- `git commit -m "Explain"`: local repository(.git)에 올려준다.
- `git push origin master`: github에 올려준다. 여기부터는 내 컴퓨터가 아님!

![image](https://user-images.githubusercontent.com/61652163/123497521-dac1aa00-d668-11eb-9c9d-c262c51e532f.png)



- `touch .gitignore`: git올릴 때 필요없는 파일 없애준다. *참고: [gitignore.io](https://www.toptal.com/developers/gitignore)

#### vi

vim 에디터를 사용하여 편집

수정(i), 나가기(esc), 쓰고 나가기(shift+: wq) 등 단축키를 사용

연습할 수 있는 사이트: [빔어드벤쳐](https://vim-adventures.com/)



#### 권한 부여

github -> project directory -> settings -> invite a collaborator

email을 통한 수락 후 push 가능하다.



#### Clone

다른 컴퓨터에서 작업할 때 사용한다.

`git clone <복사한 주소>`: 복사한 주소의 이름으로 폴더가 생긴다. 

`git pull origin master`: 코드를 깃허브에서 당겨온다.



#### Procedure

`git init`

`git add .`

`git commit -m "explain"`

`git remote add origin <주소복사>`

`git push origin master`

`git pull origin master`



#### Branch

`git checkout <commit name?>`: 과거로 돌아간다. *git log를 사용해 알 수 있다.

`git checkout master`: 현재의 코드로 돌아간다.

`git branch`: 현재 있는 branch의 목록을 보여주는 명령어

`git branch -c <branch name>`: branch를 생성(create)하는 명령어

`git switch <branch name>`: branch를 이동한다.



#### Merge

`git switch master`

`git merge <branch name>`












