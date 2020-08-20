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



#### Git

- `git init`: 깃저장소를 생성한다.
- `git status`: 깃의 상태를 보여준다.
- `git add <Filename>`: working directory에서 staging area로 올린다.
- `git commit -m "Explain"`: local repository(.git)에 올려준다.
- `git push origin master`: github에 올려준다. 여기부터는 내 컴퓨터가 아님!

<img src="command.assets/git_transaction.png" alt="git_transaction" style="zoom:80%;" />



#### vi

vim 에디터를 사용하여 편집

수정(i), 나가기(esc), 쓰고 나가기(shift+: wq) 등 단축키를 사용

연습할 수 있는 사이트: [빔어드벤쳐](https://vim-adventures.com/)











