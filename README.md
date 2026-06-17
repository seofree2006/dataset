## 프로젝트 소개
물류창고 로봇 동선 최적화 시뮬레이터

## 개발 환경
- Language: C
- IDE: Visual Studio Code
- OS: Windows

## 팀원 소개
| 이름 | 역할 |
|---|---|
| 서종훈 | 아이디어 구상, 코드 작성 |
| 진민서 | 아이디어 구상, 코드 피드백, 주석 처리 |

## 주요 기능
- 작업 순서 정하기
- 상품 위치 찾기
- 목적 물품 꺼내기
- 출하 트럭 대기열

## 프로젝트 구조
project/ 

 ├── main.c 
 ├── struct.c 
 ├── tree.c 
 ├── stack.c
 ├── queue.c
 ├── function.c
 └── README.md
 
## 실행 방법
cl main.c struct.c tree.c stack.c queue.c function.c /Fe:project.exe

project.exe
 
## 실행 화면 예시
물류창고 로봇 시뮬레이터
 ├── [1] 주문 접수 (일반 주문 생성 및 큐 진입)
 ├── [2] 로봇 작업 수행
 │    ├── 이진 탐색 트리(BST) 기반 상품 위치 검색
 │    └── 스택(Stack) 기반 선반 인출 및 롤백
 ├── [3] 트럭 출하 도크 관리 (출하 큐 FIFO 처리)
 └── [4] 시뮬레이터 안전 종료
 
## 어려웠던 점
 - 인코딩 지시어 이용
 - 한글 이름 변환 매핑
 
## 느낀 점
여러 자료구조의 실제 활용 방법을 이해할 수 있었다.
