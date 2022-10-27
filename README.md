# 1. 프로젝트 간단 요약
## Spring을 활용하여 게시판을 구현

# 2. 프로젝트 정보 / 개요
## 진행기간 : 3개월
## 진행목표 : Spring을 활용한 게시판 완성
## 팀원 : 민장규, 김인후, 이재훈

## 3.프로젝트 설명

<img src="data:image/jpeg;base64,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">

