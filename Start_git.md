# AWS

계정 : ysh01023327260@gmail.com
> 까먹지 좀 말자...



## 깃 시작

```bash
# 깃 시작(초기화)
ITWILL@DESKTOP-7JIVS4K MINGW64 /d/codebuild_sample (master)
$ git init

# 파일 추가
ITWILL@DESKTOP-7JIVS4K MINGW64 /d/codebuild_sample (master)
$ git add .
warning: in the working copy of '.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'babel.config.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'jsconfig.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'package-lock.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'package.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'public/index.html', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/App.vue', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/components/HelloWorld.vue', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'src/main.js', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'vue.config.js', LF will be replaced by CRLF the next time Git touches it

# 브런치 main 으로 변경
ITWILL@DESKTOP-7JIVS4K MINGW64 /d/codebuild_sample (master)
$ git branch -M main

# 깃 사용자 설정.이메일
ITWILL@DESKTOP-7JIVS4K MINGW64 /d/codebuild_sample (main)
$ git config --global user.email "pine01090757260@gmail.com"

# 깃 사용자 설정.이름
ITWILL@DESKTOP-7JIVS4K MINGW64 /d/codebuild_sample (main)
$ git config --global user.name "PineYoo"

# origin 원격 저장소 연결(등록)
ITWILL@DESKTOP-7JIVS4K MINGW64 /d/codebuild_sample (main)
$ git remote add origin https://github.com/PineYoo/codebuild-sample.git

# 깃 메인에 푸시(깃 서버에 푸쉬한다)
ITWILL@DESKTOP-7JIVS4K MINGW64 /d/codebuild_sample (main)
$ git push -u origin main

error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/PineYoo/codebuild_sample.git'

# 추가된 파일이 없어서 그랬던 것 같다?
ITWILL@DESKTOP-7JIVS4K MINGW64 /d/codebuild_sample (main)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

ITWILL@DESKTOP-7JIVS4K MINGW64 /d/codebuild_sample (main)
$ git commit -m "first commit"
[main (root-commit) f6c021d] first commit
 1 file changed, 24 insertions(+)
 create mode 100644 README.md

ITWILL@DESKTOP-7JIVS4K MINGW64 /d/codebuild_sample (main)
$ git log
commit f6c021dc9049c755660da310262010f02b51b72f (HEAD -> main)
Author: PineYoo <pine01090757260@gmail.com>
Date:   Fri Mar 28 16:21:56 2025 +0900

    first commit

ITWILL@DESKTOP-7JIVS4K MINGW64 /d/codebuild_sample (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 398 bytes | 398.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/PineYoo/codebuild_sample.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

```