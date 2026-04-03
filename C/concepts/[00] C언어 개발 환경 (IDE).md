# Chapter 00 - C언어 개발 환경 (IDE)

## IDE란?

#### IDE (Integrated Development Environment)
-  코드 작성, 실행, 디버깅을 한 번에 할 수 있는 개발 도구
-  코드를 작성하고 실행까지 도와주는 프로그램

---

### 1. Visual Studio Code (추천)


#### ① VS Code 설치

- 👉 [[공식 사이트 접속]](https://code.visualstudio.com/)
- Windows 버전 다운로드 및 설치

#### ② GCC 컴파일러 설치

- VS Code는 컴파일 기능이 없어서 따로 설치
- MinGW-w64 다운로드 [[링크]](https://www.mingw-w64.org/)
- 설치 진행 (기본 설정 OK)
- 설치 경로 확인 (예: C:\mingw64\bin)

#### ③ 환경 변수 설정

- “환경 변수” 검색 → 시스템 환경 변수 편집
- Path 선택 → 편집
- MinGW bin 경로 추가
- C:\mingw64\bin

#### ④ 설치 확인
```
gcc --version
```
- 버전 나오면 성공

#### ⑤ VS Code 확장 설치

- C/C++ Extension Pack (코드 자동완성, 오류 표시 기능 제공)
- code runner (버튼으로 코드 실행 가능)

#### ⑥ 코드 작성

```c
#include <stdio.h>

int main() {
    printf("Hello, C!\n");
    return 0;
}
```

#### ⑦ 코드 실행

- 우측 상단 ▶ 버튼 클릭  
(단축키: Ctrl + Alt + N)

---

### 2. Dev-C++

#### ① Dev-C++ 설치

- 👉 [[공식 사이트 접속]](https://sourceforge.net/projects/dev-cpp/)
- Windows 버전 다운로드 및 설치

#### ② 프로그램 실행

- Dev-C++ 실행
- 처음 실행 시 기본 설정은 그대로 진행

#### ③ 새 파일 생성

- 상단 메뉴 → File → New → Source File

#### ④ 코드 작성

```c
#include <stdio.h>

int main() {
    printf("Hello, C!\n");
    return 0;
}
```

#### ⑤ 코드 실행

- 상단 메뉴 → Execute → Compile & Run
- 단축키: F11

---