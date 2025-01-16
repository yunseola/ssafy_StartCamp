# 헤더
## 헤더2
### 헤더3
#### 헤더4

# ordered 리스트
1. tab 눌러보세요
2. 엔터 눌러보세요
   1. tab 누르면 2-1번
   2. 2-2번
3. 3번
   
# unordered 리스트
+ -기호 또는 +기호 또는 *기호
- 엔터
   - tab키 누르기
* unordered 리스트

# 체크 리스트 만들기
- [ ] 토스트
- [x] 당근
- [x] 양파
- [ ] 라면

# 코드 블럭 백틱 3번
```python
print('hello world')
```

# 링크 url 걸기
[네이버](http://www.naver.com)

# 이미지 걸기
![고양이](https://search.pstatic.net/common/?src=http%3A%2F%2Fblogfiles.naver.net%2FMjAyNDExMTRfMjUw%2FMDAxNzMxNTYwODY3MDUx.jz2JfqDvZt-AUZofrUG-MaxIiAVvWMbGPcar1-gjf8Mg.56cu4y7bzYJbwop1lk7tfJHv6cKFp8B_J7QYcqfEUGog.JPEG%2F3d30b561a675a866944a7fe64b1f2e3f.jpg&type=sc960_832)

# 이미지 걸기2
![강아지](./dog.jpg)

# 굵게 표현하기
__굵은 글씨__
중간에 **굵은 글씨**를 넣기

# 기울기 표현하기
_기울기 글씨_
중간에 *기울기 글씨*를 넣기

# 굵게 및 기울임
___굵게 및 기울임___
중간에 ***굵게 및 기울임***을 넣기기

# 최소선
~~취소선~~

# 수평선
---

# markdown 왜 배울까?
github에 프로젝트 올릴 때 README.md 파일에 활용

# GUI, CLI(Command Line Interface)
I : interface -> 대상을 제어하는 수단 = 리모컨같은 느낌낌

Window OS의 interface
GUI = 'Windows Shell'
CLI = 'Power shell', '명령프롬포트(cmd)'

Linux OS의 interface
GUI = 'GNOME'
CLI = 'Bash' -> 장점: Tab키 자동완성이 가능해서 사용하기 편리함

Git 다룰 때 interface
GUI = 'Github Desktop', '소스트리'
CLI = 'git bash'

GUI 장점 -> 보기 편함, 친숙함 / 복잡한 분석(Graph 같은 것)을 할 때 보기 좋다
CLI 장점 -> 빠르다(Commit 명령어 2~3초면 끝) / 계속 사용된다(20년 전, 현재, 미래 동일)

# IDE
- Python: PyCharm, 쥬피터노트북
- C#: Visual Studio
- Java: IntelliJ
  
VScode : IDE X -> 텍스트 에디터: 익스텐션을 추가해서 IDE처럼 사용 중

# Git Bash
MINGW: Minnimal GNU for Windows -> 윈도우 환경에서 리눅스에 쓰이는 툴들을 쓸 수 있게 가볍게 만든 프로젝트

리눅스는 항상 HOME 디렉토리 : ~
cd ~ : 홈 디렉토리
cd - : 뒤로가기
cd .. : 상위 디렉토리
touch : 파일 생성
mkdir : 폴더(디렉토리) 생성
start : 파일 열기
rm : 삭제
cp : 복사

절대경로 : ~/Desktop/practice/practice3
상위경로 : ./practice3
          ../practice/practice3

# git(분산 버전 관리 시스템)
git init : git 시작
rm -rf .git : git 삭제 (git 종료)

git config --global user.name "이름"
git config --global user.email "이메일일"

git add . : staging area에 올리기
git status : staging area 작업 파일 확인

git commit -m "메시지명" : repository에 올리기
git log : repository 작업 
