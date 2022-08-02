case 1. 
README.md 파일을 만든 저장소에 로컬 저장소 연결 후 
전체를 push 하려고 할 때 에러 발생

To https://github.com/seongeunjo/TIL.git
 ! [rejected]        main -> main (non-fast-forward)     
error: failed to push some refs to 'https://github.com/seongeunjo/TIL.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


임시적인 방법.
$ git push -u origin +main

READ.md 파일은 사라진다.