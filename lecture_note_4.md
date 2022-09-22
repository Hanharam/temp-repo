# **Linux**

- runs on embedded systems and mobile systems(Android)
- Runs on CLI(CommandLineInterface), but many distributions support GUIs as well
- Secure and stable
 
---

### **Shell command**

#### cd
경로를 이동한다.

#### ls

현재 디렉터리의 파일들을 보여준다. (**L**ist **S**egments)

-a : .으로 시작하는 파일, 폴더들까지 전체 출력
-l : 권한, 소유자, 만든 날짜와 용량까지 풀력
-h : 용량을 사람이 읽기 쉽도록 GB, MB로 변환

#### pwd

현재 위치의 절대 경로를 보여준다. (**P**rint **W**orking **D**irectory)

#### man
쉘 커맨드의 메뉴얼을 보여준다.(**man**ual)

#### mkdir

폴더 생성(**m**a**k**e **dir**ectory)

#### cp
**C**o**p**y
cp 복사할파일 복사될파일

-r : 디렉토리를 복사할 때 안에 파일이 있으면 재귀적으로 복사
-f : 강제로 실행

#### mv
**M**o**v**e
파일, 폴더를 이동한다.
이름을 변경한다.

#### rm
파일, 폴더를 영구적으로 지운다.

rm 지울파일 지울파일

-i: 파일이 지워지기 전에 유저에게 보임
-r: 디렉토리 안에 있는 컨텐츠도 같이 삭제

#### wildcards

\*: 모든 파일이름
g\*: g로 시작하는 파일이름
b\*.txt: b로 시작하고 .txt로 끝나는 파일 이름
data???: data로 시작하고 그 뒤에 정확히 3글자 있는 파일 이름

---

```sh
tip: rm으로 파일 제거하기 전에 ls로 지울 파일 이름 확인하기
```
