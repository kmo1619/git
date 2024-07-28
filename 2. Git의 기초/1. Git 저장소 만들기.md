## Git 저장소 만들기
1. 아직 버전관리를 하지 않는 **로컬 디렉토리** 하나를 선택해서 **Git 저장소**를 적용하는 방법
2. 다른 어딘가에서 **Git 저장소**를 **Clone** 하는 방법

### 기존 디렉토리를 Git 저장소로 만들기
```console
$ cd /[Git저장소로 만들 폴더 위치]
$ git init
```
- 이 명령은 .git이라는 하위 디렉토리를 만듬.
- .git 디렉토리에는 저장소에 필요한 뼈대 파일이 들어있음.
- Git이 파일을 귄리하기 위해 저장소에 파일을 추가하고 커밋해야 함.
```console
$ git add *.c
$ git add LICENSE
$ git commit -m '[커밋 내역 메모]'
```

### 기존 저장소를 Clone 하기
- 다른 프로젝트에 참여하거나 Git 저장소를 복사하고싶을때```git clone```명령을 사용함.
```console
$ git clone [git url]
```