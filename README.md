# test

# Git

# git의 장점
    * 로컬 저장소를 따로 둔다. 인터넷이 끊겨 있어도 commit 가능

    * 로컬에서 하고 서버에 올릴 때 동기화 하는 방식.

    * push : 서버 올리기

# 서버에서
    * 레포지터리 복사? git bash에서 서버 접속해서 
```
    # 없는 폴더에서 가져오기. 이미 폴더 있으면 pull 사용한다.
    git clone https://github.com/flaallae/test.git

    cd test/

    echo "hi" > a.txt

    cat a.txt

    git add -A

    git commit -m "xx"

    # 레포지터리로 보내기
    git push
    
```

    

    
