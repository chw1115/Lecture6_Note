# Lecture6_Note

## Git config : First-time setup
1) system level: -- system option. Affects all uses and repositories on the system // 거의 안쓴다
   **file :/etc/gitconfig**
2) Global (user) level: -- global option. Affects all repositories of a current user // 자주쓴다
   **file:~/.config/git/config**
3) Local level: -- option. Specific to the current repository // 현재 일하고있는 폴더에 저장
   **file:.git/gitconfig**

   // $ git config --list == configuration에 관한 정보확인

#### git init 
현재 working directory 새로운 repository만들기
### git status
repository의 현재상태 확인
### git add
특정한 file을 staging area로 올린다
//working directory에 있는 모든 file을 staging area로 올리고 싶다면 **git add .**
** git add [file name](unstaging 하고싶은 파일)
### git rm -- cached [file name]
//staging은 했는데 하고싶지 않은 file을 제외하고 싶을때 (unstaging)
### gitignore
//특정 file이나 directory를 무시하고 싶을때 

### Ignnoring regular expression
*.a : 확장자가 a인 모든파일 무시
build/ : build안의 모든 파일 무시
doc/*.txt: doc안의 모든 txt파일 무시
doc/**/*.pdf: doc안의 pdf파일을 무시


/// nano .(명령어) --> 메모장을 열어 파일의 내용을 수정할때 사용
