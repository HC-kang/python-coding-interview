# python-coding-interview


## 개요
&nbsp;코딩 테스트 준비 및 알고리즘을 익히기 위해 책만 출판사의 [파이썬 알고리즘 인터뷰](https://www.onlybook.co.kr/entry/algorithm-interview)를 보며 공부한 내용을 정리한다.


## 기본 사항
- 리트코드 기본 라이브러리를 항상 불러올 것
```
import collections
import heapq
import functools
import itertools
import re
import sys
import math
import bisect
from typing import *
```
- class-method 형태가 아닌 함수 형태로 풀이 작성 


## 관련 링크
- 파이썬 알고리즘 인터뷰 책 소개: https://www.onlybook.co.kr/entry/algorithm-interview
- 파이썬 알고리즘 인터뷰 GitHub 저장소: https://github.com/onlybooks/algorithm-interview
- 파이썬 알고리즘 인터뷰 정오표: https://www.onlybook.co.kr/entry/algorithm-interview-errata


## 예제

| 여부 | 제목                                                         | 난이도 | 장                            |
| ---- | ------------------------------------------------------------ | ------ | ----------------------------- |
| [O]  | [유효한 팰린드롬](https://leetcode.com/problems/valid-palindrome/) | ★      | 6장. 문자열 조작              |
| [O]  | [문자열 뒤집기](https://leetcode.com/problems/reverse-string/) | ★      | 6장. 문자열 조작              |
| [O]  | [로그 파일 재정렬](https://leetcode.com/problems/reorder-data-in-log-files/) | ★      | 6장. 문자열 조작              |
| [O]  | [가장 흔한 단어](https://leetcode.com/problems/most-common-word/) | ★      | 6장. 문자열 조작              |
| [O]  | [그룹 애너그램](https://leetcode.com/problems/group-anagrams/) | ★★     | 6장. 문자열 조작              |
| [O]  | [가장 긴 팰린드롬 부분 문자열](https://leetcode.com/problems/longest-palindromic-substring/) | ★★     | 6장. 문자열 조작              |
| [O]  | [두 수의 합](https://leetcode.com/problems/two-sum/)         | ★      | 7장. 배열                     |
| [O]  | [빗물 트래핑](https://leetcode.com/problems/trapping-rain-water/) | ★★★    | 7장. 배열                     |
| [O]  | [세 수의 합](https://leetcode.com/problems/3sum/)            | ★★     | 7장. 배열                     |
| [O]  | [배열 파티션 I](https://leetcode.com/problems/array-partition-i/) | ★      | 7장. 배열                     |
| [O]  | [자신을 제외한 배열의 곱](https://leetcode.com/problems/product-of-array-except-self/) | ★★     | 7장. 배열                     |
| [O]  | [주식을 사고팔기 가장 좋은 시점](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | ★      | 7장. 배열                     |
| [O]  | [팰린드롬 연결 리스트](https://leetcode.com/problems/palindrome-linked-list/) | ★      | 8장. 연결 리스트              |
| [O]  | [두 정렬 리스트의 병합](https://leetcode.com/problems/merge-two-sorted-lists/) | ★      | 8장. 연결 리스트              |
| [O]  | [역순 연결 리스트](https://leetcode.com/problems/reverse-linked-list/) | ★      | 8장. 연결 리스트              |
| [O]  | [두 수의 덧셈](https://leetcode.com/problems/add-two-numbers/) | ★★     | 8장. 연결 리스트              |
| [O]  | [페어의 노드 스왑](https://leetcode.com/problems/swap-nodes-in-pairs/) | ★★     | 8장. 연결 리스트              |
| [O]  | [홀짝 연결 리스트](https://leetcode.com/problems/odd-even-linked-list/) | ★★     | 8장. 연결 리스트              |
| [O]  | [역순 연결 리스트 II](https://leetcode.com/problems/reverse-linked-list-ii/) | ★★     | 8장. 연결 리스트              |
| [O]  | [유효한 괄호](https://leetcode.com/problems/valid-parentheses/) | ★      | 9장. 스택, 큐                 |
| [O]  | [중복 문자 제거](https://leetcode.com/problems/remove-duplicate-letters/) | ★★★    | 9장. 스택, 큐                 |
| [O]  | [일일 온도](https://leetcode.com/problems/daily-temperatures/) | ★★     | 9장. 스택, 큐                 |
| [O]  | [큐를 이용한 스택 구현](https://leetcode.com/problems/implement-stack-using-queues/) | ★      | 9장. 스택, 큐                 |
| [O]  | [스택을 이용한 큐 구현](https://leetcode.com/problems/implement-queue-using-stacks/) | ★      | 9장. 스택, 큐                 |
| [O]  | [원형 큐 디자인](https://leetcode.com/problems/design-circular-queue/) | ★★     | 9장. 스택, 큐                 |
| [O]  | [원형 데크 디자인](https://leetcode.com/problems/design-circular-deque/) | ★★     | 10장. 데크, 우선 순위 큐      |
| [O]  | [k개 정렬 리스트 병합](https://leetcode.com/problems/merge-k-sorted-lists/) | ★      | 10장. 데크, 우선 순위 큐      |
| [O]  | [해시맵 디자인](https://leetcode.com/problems/design-hashmap/) | ★      | 11장. 해시 테이블             |
| [O]  | [보석과 돌](https://leetcode.com/problems/jewels-and-stones/) | ★      | 11장. 해시 테이블             |
| [O]  | [중복 문자 없는 가장 긴 부분 문자열](https://leetcode.com/problems/longest-substring-without-repeating-characters/) | ★★     | 11장. 해시 테이블             |
| [O]  | [상위 K 빈도 요소](https://leetcode.com/problems/top-k-frequent-elements/) | ★★     | 11장. 해시 테이블             |
| [O]  | [섬의 개수](https://leetcode.com/problems/number-of-islands/) | ★★     | 12장. 그래프                  |
| [O]  | [전화 번호 문자 조합](https://leetcode.com/problems/letter-combinations-of-a-phone-number/) | ★★     | 12장. 그래프                  |
| [O]  | [순열](https://leetcode.com/problems/permutations/)          | ★★     | 12장. 그래프                  |
| [O]  | [조합](https://leetcode.com/problems/combinations/)          | ★★     | 12장. 그래프                  |
| [O]  | [조합의 합](https://leetcode.com/problems/combination-sum/)  | ★★     | 12장. 그래프                  |
| [O]  | [부분 집합](https://leetcode.com/problems/subsets/)          | ★★     | 12장. 그래프                  |
| [O]  | [일정 재구성](https://leetcode.com/problems/reconstruct-itinerary/) | ★★     | 12장. 그래프                  |
| [O]  | [코스 스케줄](https://leetcode.com/problems/course-schedule/) | ★★     | 12장. 그래프                  |
| [O]  | [네트워크 딜레이 타임](https://leetcode.com/problems/network-delay-time/) | ★★     | 13장. 최단 경로 문제          |
| [O]  | [K 경유지 내 가장 저렴한 항공권](https://leetcode.com/problems/cheapest-flights-within-k-stops/) | ★★     | 13장. 최단 경로 문제          |
| [O]  | [이진 트리의 최대 깊이](https://leetcode.com/problems/maximum-depth-of-binary-tree/) | ★      | 14장. 트리                    |
| [O]  | [이진 트리의 직경](https://leetcode.com/problems/diameter-of-binary-tree/) | ★      | 14장. 트리                    |
| [O]  | [가장 긴 동일 값의 경로](https://leetcode.com/problems/longest-univalue-path/) | ★      | 14장. 트리                    |
| [O]  | [이진 트리 반전](https://leetcode.com/problems/invert-binary-tree/) | ★      | 14장. 트리                    |
| [O]  | [두 이진 트리 병합](https://leetcode.com/problems/merge-two-binary-trees/) | ★      | 14장. 트리                    |
| [O]  | [이진 트리 직렬화 & 역직렬화](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/) | ★★★    | 14장. 트리                    |
| [O]  | [균형 이진 트리](https://leetcode.com/problems/balanced-binary-tree/) | ★      | 14장. 트리                    |
| [O]  | [최소 높이 트리](https://leetcode.com/problems/minimum-height-trees/) | ★★     | 14장. 트리                    |
| [O]  | [정렬된 배열의 이진 탐색 트리 변환](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/) | ★      | 14장. 트리                    |
| [O]  | [이진 탐색 트리(BST)를 더 큰 수 합계 트리로](https://leetcode.com/problems/binary-search-tree-to-greater-sum-tree/) | ★★     | 14장. 트리                    |
| [O]  | [이진 탐색 트리(BST) 합의 범위](https://leetcode.com/problems/range-sum-of-bst/) | ★      | 14장. 트리                    |
| [O]  | [이진 탐색 트리(BST) 노드 간 최소 거리](https://leetcode.com/problems/minimum-distance-between-bst-nodes/) | ★      | 14장. 트리                    |
| [O]  | [전위, 중위 순회 결과로 이진 트리 구축](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) | ★★     | 14장. 트리                    |
| [O]  | [배열의 K번째 큰 요소](https://leetcode.com/problems/kth-largest-element-in-an-array/) | ★★     | 15장. 힙                      |
| [O]  | [트라이 구현](https://leetcode.com/problems/implement-trie-prefix-tree/) | ★★     | 16장. 트라이                  |
| [O]  | [팰린드롬 페어](https://leetcode.com/problems/palindrome-pairs/) | ★★★    | 16장. 트라이                  |
| [O]  | [리스트 정렬](https://leetcode.com/problems/sort-list/)      | ★★     | 17장. 정렬                    |
| [O]  | [구간 병합](https://leetcode.com/problems/merge-intervals/)  | ★★     | 17장. 정렬                    |
| [O]  | [삽입 정렬 리스트](https://leetcode.com/problems/insertion-sort-list/) | ★★     | 17장. 정렬                    |
| [O]  | [가장 큰 수](https://leetcode.com/problems/largest-number/)  | ★★     | 17장. 정렬                    |
| [O]  | [유효한 애너그램](https://leetcode.com/problems/valid-anagram/) | ★      | 17장. 정렬                    |
| [O]  | [색 정렬](https://leetcode.com/problems/sort-colors/)        | ★★     | 17장. 정렬                    |
| [O]  | [원점에 K번째 가까운 점](https://leetcode.com/problems/k-closest-points-to-origin/) | ★★     | 17장. 정렬                    |
| [O]  | [이진 검색](https://leetcode.com/problems/binary-search/)    | ★      | 18장. 이진 검색               |
| [O]  | [회전 정렬된 배열 검색](https://leetcode.com/problems/search-in-rotated-sorted-array/) | ★★     | 18장. 이진 검색               |
| [O]  | [두 배열의 교집합](https://leetcode.com/problems/intersection-of-two-arrays/) | ★      | 18장. 이진 검색               |
| [O]  | [두 수의 합 II](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/) | ★      | 18장. 이진 검색               |
| [O]  | [2D 행렬 검색 II](https://leetcode.com/problems/search-a-2d-matrix-ii/) | ★★     | 18장. 이진 검색               |
| [O]  | [싱글 넘버](https://leetcode.com/problems/single-number/)    | ★      | 19장. 비트 조작               |
| [O]  | [해밍 거리](https://leetcode.com/problems/hamming-distance/) | ★      | 19장. 비트 조작               |
| [O]  | [두 정수의 합](https://leetcode.com/problems/sum-of-two-integers/) | ★★★    | 19장. 비트 조작               |
| [O]  | [UTF-8 검증](https://leetcode.com/problems/utf-8-validation/) | ★★     | 19장. 비트 조작               |
| [O]  | [1비트의 개수](https://leetcode.com/problems/number-of-1-bits/) | ★      | 19장. 비트 조작               |
| [O]  | [최대 슬라이딩 윈도우](https://leetcode.com/problems/sliding-window-maximum/) | ★★★    | 20장. 슬라이딩 윈도우         |
| [O]  | [부분 문자열이 포함된 최소 윈도우](https://leetcode.com/problems/minimum-window-substring/) | ★★★    | 20장. 슬라이딩 윈도우         |
| [O]  | [가장 긴 반복 문자 대체](https://leetcode.com/problems/longest-repeating-character-replacement/) | ★★     | 20장. 슬라이딩 윈도우         |
| [O]  | [주식을 사고 팔기 가장 좋은 시점 II](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/) | ★      | 21장. 그리디 알고리즘         |
| [O]  | [키에 따른 대기열 재구성](https://leetcode.com/problems/queue-reconstruction-by-height/) | ★★     | 21장. 그리디 알고리즘         |
| [O]  | [태스크 스케줄러](https://leetcode.com/problems/task-scheduler/) | ★★     | 21장. 그리디 알고리즘         |
| [O]  | [주유소](https://leetcode.com/problems/gas-station/)         | ★★     | 21장. 그리디 알고리즘         |
| [O]  | [쿠키 부여](https://leetcode.com/problems/assign-cookies/)   | ★      | 21장. 그리디 알고리즘         |
| [O]  | [과반수 엘리먼트](https://leetcode.com/problems/majority-element/) | ★      | 22장. 분할 정복               |
| [O]  | [괄호를 삽입하는 여러가지 방법](https://leetcode.com/problems/different-ways-to-add-parentheses/) | ★★     | 22장. 분할 정복               |
| [O]  | [피보나치 수](https://leetcode.com/problems/fibonacci-number/) | ★      | 23장. 다이나믹 프로그래밍     |
| [O]  | [최대 서브 배열](https://leetcode.com/problems/maximum-subarray/) | ★      | 23장. 다이나믹 프로그래밍     |
| [O]  | [계단 오르기](https://leetcode.com/problems/climbing-stairs/) | ★      | 23장. 다이나믹 프로그래밍     |
| [O]  | [집 도둑](https://leetcode.com/problems/house-robber/)       | ★      | 23장. 다이나믹 프로그래밍     |
| [O]  | [비밀 지도](https://programmers.co.kr/learn/courses/30/lessons/17681) | ★      | 부록 B. 카카오 공채 문제 풀이 |
| [O]  | [다트 게임](https://programmers.co.kr/learn/courses/30/lessons/17682) | ★      | 부록 B. 카카오 공채 문제 풀이 |
| [O]  | [캐시](https://programmers.co.kr/learn/courses/30/lessons/17680) | ★      | 부록 B. 카카오 공채 문제 풀이 |
| [O]  | [셔틀버스](https://programmers.co.kr/learn/courses/30/lessons/17678) | ★★     | 부록 B. 카카오 공채 문제 풀이 |
| [O]  | [뉴스 클러스터링](https://programmers.co.kr/learn/courses/30/lessons/17677) | ★★     | 부록 B. 카카오 공채 문제 풀이 |
| [O]  | [프렌즈4블록](https://programmers.co.kr/learn/courses/30/lessons/17679) | ★★★    | 부록 B. 카카오 공채 문제 풀이 |
| [O]  | [추석 트래픽](https://programmers.co.kr/learn/courses/30/lessons/17676) | ★★★    | 부록 B. 카카오 공채 문제 풀이 |

<a href='#python-coding-interview'><strong><small>목차로 돌아가기</small></strong></a>


---


## References

- https://github.com/yangju0411/algorithm_interview
- https://github.com/Winters0727/Python-Algorithm-Interview
- https://github.com/jaeyun95/ai-tech-interview
