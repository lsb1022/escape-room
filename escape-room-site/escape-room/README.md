# 탈출의 자료구조

CCC 2020 S2 "Escape Room"을 스택 DFS로 풀고, 스택 5가지·큐 5가지·재귀 DFS의 성능을 비교한 발표 자료예요.

- `index.html` 메인: 문제, DFS 따라가기, 실제 성능, 큐·재귀 비교, 언제 뭘 쓸까
- `two-cells.html` 100만 칸 중 2칸만 바꾸면 일어나는 일
- `random.html` 편향 없는 난수 20개로 다시 잰 결과

측정 환경: Ubuntu 24.04.5 · Intel Xeon 2 vCPU · g++-12 12.4.0 · `-std=c++17 -O2 -Wall -Wextra`
