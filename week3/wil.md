# 목차
1. Log
2. Status
3. Commit --amend
2. Reset
3. Revert

# 1. Log
## 개요
Commit History를 볼 수 있는 명령어.</br>
--oneline 옵션 사용 시 각 커밋을 한 줄에 표시. </br>
## 표시 정보
1. Commit ID</br>
2. 현재 작업중인 브랜치</br>
3. 커밋의 이름
4. 커밋 순서대로 표시되므로, 순서도 알 수 있음


# 2. Status
## 상태 종류
1. Untracked : 깃이 관리중인 파일이 아님 </br>
2. Staged : Stage영역으로 반영되지 않은 수정사항이 없음 </br>
3. Modified : Stage영역으로 반영되지 않은 수정사항이 있음 </br>
4. Unmodifed : 가장 마지막에 커밋된 상태에서 수정되지 않음 </br>

# 3. Commit --amend
## 의미
Commit의 내용을 수정하고자 할 때, 새로운 커밋으로 덮어씌우는 옵션</br>
이전 커밋은 브랜치에서 완전히 사라지므로, 타인의 커밋을 건드리지 않도록 주의

# 4. Reset
## 의미
커밋을 제거하는 명령어
## Soft
커밋을 취소하여, Staging Area로 돌아감
## mixed
커밋을 취소하여, Working Directory로 돌아감
## hard
커밋을 취소하여, 완전히 제거함
##
완전히 사라져버리므로, 협업에서 바람직하지 않은 명령어


# 5. Revert
## 의미
커밋을 새로운 커밋을 생성하여 되돌림
