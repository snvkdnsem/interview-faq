#최초 프로젝트 생성시 수행하는 작업 

##1.작업폴더 및 파일생성
------------------------------------
```bash
mkdir interview-faq
cd interview-faq
echo "-# interview0-faq" >> README.md
```

##2. 로컬 저장소 생성
```bash
git init
```

##3. 백업
```bash
git add --all
git status
git commit -m "#1"
git log
```

##4. 원격저장소 등록 (연결)
```bash
git remote add origin
https://github.com/songsoojin/interview-faq.git
git remotr -v
```

##5. 로컬 저장소 --업로드 ==> 원격저장소
```bash
git push -u origin master
```

#프로젝트 중간에 수행하는 작업

##1. 작업폴더 및 파일 생성
에디터로 수행하는 작업

##2. 백업
```bash
git add --all
git commit -m "#1"
```

##3. 로컬 저장소 == 업로드 ==> 원격 저장소
등록된 원격 저장소가 하나일 때 간단하게 업로드가 가능하다.

```bash
git push
```

push를 거부하는 경우에 대처방법은 먼저 pull을 수행하고 
그 후 push 를 한다.

```bash
git pull
git push
```








